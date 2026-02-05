# Connector Usage Guide

## SharePoint Connector

**When to use**: Reading/writing lists and documents

**Authentication**: User credentials (recommended) or service account

**Common Actions**:
- Get items: Retrieve list data
- Create item: Add new list entry
- Update item: Modify existing entry
- Get files: Retrieve documents

**Rate Limits**: ~600 requests per minute per user

**Best Practices**:
- Use "Get items" with filters rather than retrieving all items
- Cache results when possible
- Handle errors gracefully

## Microsoft Teams Connector

**When to use**: Posting messages, creating channels, managing team content

**Authentication**: User credentials

**Common Actions**:
- Post message: Send notification to channel
- Create channel: Set up new team channel
- Get messages: Retrieve conversation history

**Best Practices**:
- Use adaptive cards for rich messages
- Don't spam channels with too many notifications
- Consider using Power Automate for complex workflows

## Power Automate

**When to use**: Multi-step processes, scheduled tasks, complex data transformation

**Examples**:
- Create item in SharePoint + send Teams notification + create Planner task
- Daily digest of agent usage
- Automated duplicate checking

**Best Practices**:
- Document flow purpose and logic
- Add error handling to every action
- Use variables for reusable values
- Test with sample data first

## Rate Limits and Throttling

All connectors have limits. Document expected usage patterns:

- **Low volume**: &lt; 100 calls per day
- **Medium volume**: 100-1000 calls per day  
- **High volume**: &gt; 1000 calls per day

For high volume, implement retry logic with exponential backoff.
