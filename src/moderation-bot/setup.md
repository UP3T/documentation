# Setup and Configuration for the "User Joining Verification" Bot

Setting up the "User Joining Verification" bot is a straightforward process. By following these steps, you'll have the bot up and running on your Discord server in no time.

## UP3T Dashboard Configuration

1. Navigate to the [UP3T Dashboard](https://app.up3t.com/mainBot).
![Dashboard Screenshot](./path_to_screenshot/dashboard.png){: style="max-width:100%;" }

2. Locate the floating "+" button at the bottom right corner of the page and click on it.
![+ Button Screenshot](./path_to_screenshot/plus_button.png){: style="max-width:100%;" }

3. A modal will appear, prompting you to choose a bot. Select "User Joining Verification" from the list.
![Select Bot Screenshot](./path_to_screenshot/select_bot.png){: style="max-width:100%;" }

4. Click "Next".

5. You'll be asked to select a channel. For the purpose of this setup, choose the "Welcome" channel located inside the "welcome" category.
![Select Channel Screenshot](./path_to_screenshot/select_channel.png){: style="max-width:100%;" }

6. Click "Next" again. The backend will now handle the installation of the bot.

## Discord Server Configuration

Before the bot can function correctly, you need to ensure that your Discord server is set up appropriately:

### Channel Creation

- Create a category named "welcome".
![Create Category Screenshot](./path_to_screenshot/create_category.png){: style="max-width:100%;" }

- Inside the "welcome" category, create a text channel named "Welcome".
![Create Channel Screenshot](./path_to_screenshot/create_channel.png){: style="max-width:100%;" }

### Channel Permissions

- Ensure that the "Welcome" channel is set up so that new users can only see this channel upon joining.
![Channel Permissions Screenshot](./path_to_screenshot/channel_permissions.png){: style="max-width:100%;" }

### Role Creation

- Create a role named "Verified".
![Create Role Screenshot](./path_to_screenshot/create_role.png){: style="max-width:100%;" }

### Bot Permissions

- Ensure that the bot has the necessary permissions to view, send messages, and manage roles in the "Welcome" channel.
![Bot Permissions Screenshot](./path_to_screenshot/bot_permissions.png){: style="max-width:100%;" }

## Verification

Once you've completed the above steps, the bot will handle the verification process. New members will be greeted with the image-based challenge in the "Welcome" channel. Upon successful verification, they will be granted the "Verified" role, allowing them access to the rest of the server.

### Important Notes

- Ensure that the "Verified" role is positioned below the bot's role in the server's role hierarchy. This ensures that the bot can assign the "Verified" role to users.
![Role Hierarchy Screenshot](./path_to_screenshot/role_hierarchy.png){: style="max-width:100%;" }

- Regularly check the bot's permissions. If there are any updates or changes to the Discord platform, you might need to adjust the bot's permissions accordingly.
