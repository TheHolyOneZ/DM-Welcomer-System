# DM-Welcomer-System
The DM Welcomer System allows server administrator to create highly customizable welcome messages that are automatically sent to new members when they join the server Unlike traditional welcome messages posted in channels, this system delivers a personal touch by sending messages directly to the users DMs ensuring they receive important server info
> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)
# 🔔 DM Welcomer System

A comprehensive Discord bot extension that sends personalized welcome messages directly to new members via private messages (DMs).

## 📋 Description

The DM Welcomer System allows server administrators to create highly customizable welcome messages that are automatically sent to new members when they join the server. Unlike traditional welcome messages posted in channels, this system delivers a personal touch by sending messages directly to the user's DMs, ensuring they receive important server information and feel welcomed from the moment they join.

---

## ✨ Key Features

### 🎨 **Highly Customizable Messages**
- Support for rich Discord embeds with custom colors, images, and fields
- Plain text message support for simpler approaches
- Advanced placeholder system for dynamic content
- JSON-based configuration for maximum flexibility

### 🔧 **Easy Management**
- Interactive setup wizard with step-by-step guidance
- Toggle system to quickly enable/disable the welcomer
- Real-time preview of welcome messages
- One-click configuration import/export

### 📊 **Statistics & Monitoring**
- Track successful message deliveries
- Monitor failed delivery attempts
- Calculate success rates and performance metrics
- View detailed statistics dashboard

### 🛡️ **Robust & Reliable**
- Comprehensive error handling for failed DM deliveries
- Admin permission verification
- Safe JSON parsing and validation
- Automatic fallback handling

---

## 🎯 Hybrid Command System

This extension supports both **prefix commands** (`!command`) and **slash commands** (`/command`) for maximum compatibility and user preference.

### 📝 Available Commands

| Command | Prefix | Slash | Description |
|---------|--------|-------|-------------|
| **Main Setup** | `!dm_welcome` | `/dm_welcome_setup` | Open the interactive setup menu |
| **Toggle System** | `!dm_welcome toggle` | `/dm_welcome_toggle` | Enable or disable the DM welcomer |
| **View Status** | `!dm_welcome status` | `/dm_welcome_status` | Check current system status and stats |
| **Test Message** | `!dm_welcome_test [user]` | N/A | Send a test welcome message |
| **Export Config** | `!dm_welcome_export` | N/A | Export current configuration as JSON |
| **Reset Stats** | `!dm_welcome_reset_stats` | N/A | Reset all statistics to zero |

---

## 🚀 What It Can Do

### 📨 **Automatic Welcome Messages**
- Sends personalized DMs to every new member
- Supports multiple message formats (embed, text, or hybrid)
- Handles member join events in real-time
- Gracefully handles users with disabled DMs

### 🎨 **Rich Content Support**
- **Embeds**: Create beautiful, formatted messages with colors, images, and structured content
- **Images**: Add thumbnails, banners, and custom graphics
- **Fields**: Organize information in neat, inline or full-width sections
- **Custom Colors**: Match your server's branding and theme

### 🔄 **Dynamic Placeholders**
Replace static text with dynamic information:
- `{user}` - Full user mention (@Username#1234)
- `{username}` - Username only (Username)
- `{display_name}` - Server display name or nickname
- `{server}` - Server name
- `{member_count}` - Current total member count

### 📁 **JSON Configuration System**
- Upload custom JSON files for complex configurations
- Multiple pre-built templates for quick setup
- Export and share configurations between servers
- Validate JSON structure automatically

### 📊 **Comprehensive Analytics**
- **Success Tracking**: Monitor how many messages were delivered successfully
- **Failure Analysis**: Track and understand delivery failures
- **Performance Metrics**: Calculate success rates and delivery statistics
- **Historical Data**: View when the last message was sent

---

## 🎯 Use Cases

### 🏢 **Professional Servers**
- Welcome new employees with company information
- Share important policies and guidelines
- Provide contact information for support

### 🎮 **Gaming Communities**
- Introduce server rules and game-specific channels
- Share Discord server layout and navigation tips
- Promote upcoming events and tournaments

### 📚 **Educational Servers**
- Welcome students with course information
- Share important academic resources and links
- Provide study group and collaboration details

### 🎉 **Community Servers**
- Create warm, personal welcome experiences
- Share community guidelines and expectations
- Highlight special features and unique aspects

---

## 🛠️ Technical Capabilities

### 🔐 **Security Features**
- **Permission Verification**: Only administrators and users with "Manage Server" permissions can configure the system
- **Input Validation**: All JSON configurations are validated before saving
- **Error Handling**: Comprehensive error catching and user-friendly error messages
- **Safe Execution**: Protected against malformed data and edge cases

### ⚡ **Performance Optimized**
- **Asynchronous Processing**: Non-blocking message delivery
- **Efficient Storage**: Lightweight JSON-based configuration storage
- **Memory Management**: Optimized for servers of all sizes
- **Rate Limiting Aware**: Respects Discord's API limitations

### 🔄 **Maintenance Features**
- **Configuration Backup**: Export settings for backup purposes
- **Statistics Reset**: Clear historical data when needed
- **System Toggle**: Quickly disable during maintenance
- **Test Functionality**: Verify configurations before going live

---

## 📋 Setup Process

### 1️⃣ **Initial Configuration**
Run `!dm_welcome` or `/dm_welcome_setup` to open the interactive setup menu

### 2️⃣ **Choose Configuration Method**
- **Upload JSON**: Import a custom configuration file
- **Use Template**: Select from pre-built examples (Simple, Advanced, Text-only)
- **Manual Setup**: Create configuration step-by-step

### 3️⃣ **Preview & Test**
- Preview your welcome message before activation
- Send test messages to verify formatting
- Make adjustments as needed

### 4️⃣ **Activate System**
- Toggle the system on with `!dm_welcome toggle`
- Monitor statistics and performance
- Make adjustments based on feedback

---

## 🎨 Example Configurations

### 🟢 **Simple Welcome**
Perfect for basic server welcomes with essential information.

### 🟣 **Advanced Welcome**
Feature-rich messages with multiple sections, images, and detailed server information.

### 🟠 **Text-Only Welcome**
Clean, simple text messages for servers preferring minimal formatting.

---

## 📞 Support & Information

### 🔧 **Troubleshooting**
- Check user DM settings if messages fail to deliver
- Verify bot permissions in the server
- Ensure JSON configuration is properly formatted
- Review statistics for delivery patterns

### 📊 **Best Practices**
- Keep messages concise but informative
- Test configurations before enabling
- Monitor delivery statistics regularly
- Update placeholders when server information changes

### 🏷️ **Credits**
**Made By TheHolyOneZ**

---

*This extension provides a professional, reliable, and user-friendly solution for welcoming new members to your Discord server through personalized direct messages.*
