# 🪶 FeatherNotes

**Your Intelligent Note-Taking Companion with AI Assistance and Encryption**

FeatherNotes is a modern, feature-rich note-taking application that combines elegant design with powerful functionality. Built with JavaScript, it offers AI-powered writing assistance, encryption for sensitive notes, smart reminders, and a beautiful feather-themed interface.

## ✨ Features

### 🔐 **Secure User Management**
- User registration and authentication
- JWT-based secure sessions  
- Password hashing with bcrypt
- Personal user accounts

### 📝 **Smart Note Taking**
- Rich text editor with formatting options
- Real-time auto-save functionality
- Color-coded notes for organization
- Tag system for easy categorization
- Search functionality across all notes
- Note duplication and bulk operations

### 🤖 **AI Writing Assistant**
- Context-aware writing suggestions
- Real-time grammar and style tips
- Content enhancement recommendations  
- Smart tag suggestions based on content
- Writing pattern analysis

### 🔒 **Advanced Security**
- End-to-end note encryption
- AES encryption for sensitive content
- Encrypted note identification
- Secure data transmission

### ⏰ **Smart Reminders**
- Set custom reminders for any note
- Browser notifications support
- Time-based reminder triggers
- Reminder management dashboard
- Individual note reminders
- Automatic reminder cleanup

### 🎨 **Beautiful Interface**
- Elegant feather-themed design
- Dark and light theme support
- Responsive design for all devices
- Smooth animations and transitions
- Intuitive user experience

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation & Setup

1. **Navigate to project directory**
   ```bash
   cd d:/Ideathon
   ```

2. **Install dependencies** (if not already done)
   ```bash
   npm install
   ```

3. **Start the application**
   ```bash
   npm start
   ```

4. **Access the application**
   Open your browser and go to `http://localhost:3000`

## 📋 Usage Guide

### Getting Started
1. **Create an Account**: Register with your email and password
2. **Create Your First Note**: Click the "New Note" button or use `Ctrl+N`
3. **Write and Format**: Use the rich text editor with formatting tools
4. **Set Reminders**: Click the bell icon to set reminders for individual notes
5. **Organize**: Add tags and colors to categorize your notes

### Reminder Feature
The reminder system allows you to set custom reminders for any note:

- **Setting Reminders**: 
  - Open any note in the editor
  - Click the bell icon (🔔) in the editor toolbar
  - Choose date and time for your reminder
  - Add a custom reminder message
  - Save the reminder

- **Managing Reminders**:
  - View all reminders from the user menu
  - Get browser notifications when reminders are due
  - Delete or modify existing reminders
  - Automatic cleanup of past reminders

- **Reminder Notifications**:
  - Browser notifications (if permission granted)
  - In-app notification system
  - Visual and audio alerts
  - Click notifications to open the related note

## ⌨️ Keyboard Shortcuts

### General
- `Ctrl/Cmd + N` - New Note
- `Ctrl/Cmd + K` - Focus Search
- `Alt + T` - Toggle Theme
- `Alt + R` - Show Reminders
- `Alt + A` - AI Assistant

### Note Editing
- `Ctrl/Cmd + S` - Save Note
- `Ctrl/Cmd + B` - Bold Text
- `Ctrl/Cmd + I` - Italic Text
- `Escape` - Close Editor

## 🛡️ Security & Storage

### Data Storage
- **Local Database**: SQLite database for secure local storage
- **User Data**: All notes and reminders are stored per user account
- **Encryption**: Optional AES encryption for sensitive notes
- **Auto-backup**: Automatic local storage backup system

### Privacy
- User data isolation
- Local encryption keys
- No data sharing with third parties
- Optional encrypted notes feature

## 🐛 Troubleshooting

### Common Issues

**"http://localhost:3000" message during account creation**
- This is normal - it indicates the app is connecting to the local server
- The app uses local storage for backup and offline functionality
- Your data is securely stored in the local database

**Server connection issues**
- Ensure the server is running (`npm start`)
- Check if port 3000 is available
- Clear browser cache if needed

**Reminder notifications not showing**
- Enable notification permissions in your browser
- Check browser notification settings
- Ensure the app tab remains open for background notifications

**Notes not saving**
- Check network connection to localhost:3000
- Verify you're logged in
- Check browser console for any errors

## 📱 Features Overview

### Core Functionality
- ✅ User registration and authentication
- ✅ Create, edit, delete notes
- ✅ Rich text formatting
- ✅ Search and tag system
- ✅ Color-coded organization
- ✅ Dark/Light theme toggle

### Advanced Features
- ✅ Individual note reminders
- ✅ AI writing assistance
- ✅ Note encryption
- ✅ Auto-save functionality
- ✅ Responsive design
- ✅ Keyboard shortcuts

### Reminder System Details
- Set custom date/time for each note
- Browser notification support
- Reminder message customization
- Automatic reminder triggers
- Visual reminder management
- Integration with note editing


## 📞 Support

Having issues? Here are some solutions:

1. **Clear browser data** if experiencing login issues
2. **Refresh the page** if the interface doesn't load properly
3. **Check browser console** for any error messages
4. **Ensure JavaScript is enabled** in your browser
5. **Try a different browser** if problems persist

---

**Made with 💜 for productive note-taking**

*FeatherNotes - Your intelligent companion for organized thoughts and timely reminders.*
