# Discord Management Responsibilities

- [Channel Management](#channelmanagement)
- [User Management](#usermanagement)
- [Server Management](#servermanagement)
- [Bot Management](#botmanagement)
- [Product Management](#productmanagement)
- [Administrator Permission](#adminpermission)
- [Tips](#modtips)
- [Monitoring](#monitoring)

Administrators and Moderators have responsibilities on Discord servers to foster an enjoyable community environment and support/protect their members. As Discord server membership gets larger, more of these best practice will be relevant, especially when monetized servers. 

## Responsibilities

### Channel Management <a name="channelmanagement"></a>
- Steering user posts to appropriate channels by topic
- Management of flagged messages
- Removing messages that are against server rules or from bad actors

### User Management <a name="usermanagement"></a>
- Supporting of members experiencing issues
- Warning, kicking, user timeouts, or banning members 

### Server Management <a name="servermanagement"></a>
- Reviewing audit logs and alerts
- Troubleshooting server issues

### Bot Management <a name="botmanagement"></a>
- Use verified and well-known bots for extra functionality:
    - Member and message moderation
    - Post and announcement creation
    - Reaction roles
    - Logging and alerting
    - Server analytics
    - Monetization and product management
    - Other server or community features
- Manage and monitor bot permissions on the server
- Bot security patches and updates

### Product Management <a name="productmanagement"></a>
- If your server manages subscriptions or products:
    - Managing subscriptions
    - Product feature and uploads
    - Monetization

### Administrator Permission <a name="adminpermission"></a>
- When Discord servers are created, the account that created it is assigned the **Server Owner** classification. On a new server, this is called out by a **Crown Icon** next to the user account in the member list. If this account will be deleted or will be leaving the server, make sure to [Transfer the Server Owner](https://support.discord.com/hc/en-us/articles/216273938-How-do-I-transfer-server-ownership-) classification to another Administrator on this server. 

- For larger servers, it would be a good idea to have at least one other account that has the Administrator permission for redundancy. Use the [Create Administrators Role](https://support.discord.com/hc/en-us/articles/360000516572-Server-Ownership-The-Crown-Icon) process to accomplish this. This should also remove the crown icon from being seen by regular members (logging into the Server Owner account, that account may still see the crown icon in their view of the member list). This role should be on the top of the role hierarchy list. Make sure to limit the amount of privileged members in this Administrators role (recommend only 2 members at most). This Administrators role is not meant for Moderators which should be a separate role with far less permissions geared toward moderation tasks. 

- It is a good security practice to have a separate account that is in this Administrator Role with the Administrator permissions. This separate Discord account is only used when admin level access is needed on the server and for no other purpose. This account should have a very secure password, 2FA enabled, 2FA backup codes saved in a secure location, and a verified phone number attach to it. Keep in mind that Discord currently does not allow VOIP or landline numbers to be used. An actual phone carrier phone number will need to be used. 

### Tips <a name="modtips"></a>
- Administrator and Moderator account passwords should not be used for any other services (passwords should be unique to this Discord account).
- Administrators and Moderators should change their passwords on a regular basis.
- Administrators and Moderators should use strong authentication like 2FA or future features like security/pass keys.
- Members that are a part of the Administrator role or have the Administrator permission set should only use that account for uncommon escalated server tasks. Those individuals should have a separate account that can be used for normal member activities or light moderation. 
- Members that become Moderators should be vetted outside of Discord or with a more personal interaction (video call, other forms of media, etc.) before being promoted to Moderators. 
- Document the processes and tasks Moderators will be performing. For example, how to kick/ban members or what to do during an malicious incident. This way, Moderators will all be completing tasks the same way.
- Discord has some features to report user accounts or harmful posts. That being said, the overall feel from Discord is Moderators are given the responsibility to govern their own Discord servers and set their own server rules accordingly.
- During a security event, servers have a new beta feature to temporarily halt member joins and DMs  over a period of time. Right click on the Discord server > Security Actions to use this feature. 

<img src="./readme-files/security_actions.png" width="200px">
<br />

<img src="./readme-files/security_actions_window.png" width="500px">
<br />


## Monitoring <a name="monitoring"></a>
- Monitor the health of the [Discord Service Status and APIs](https://discordstatus.com/). This status service allows for multiple ways to get notified. It even allows for channel webhooks to be added which would be great for a moderator-only update channel. 
- Logging of server and administrative events from the Discord server via Audit logs. 
- User activity analytics
