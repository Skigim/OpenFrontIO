# OpenFrontIO VS Code Workspace Setup

This workspace has been customized for optimal OpenFrontIO game development experience.

## 🚀 Quick Start

1. **Start Development**: Press `Ctrl+Shift+P` → `Tasks: Run Task` → `🎮 Start Development`
2. **Debug Game**: Press `F5` → Select `🚀 Debug Full Game (Server + Client)`
3. **Run Tests**: Press `Ctrl+Shift+P` → `Tasks: Run Task` → `🧪 Run Tests`

## 📁 Workspace Structure

```text
.vscode/
├── settings.json       # Editor settings optimized for TypeScript/game dev
├── tasks.json         # Pre-configured tasks for building, testing, etc.
├── launch.json        # Debug configurations for server, client, and tests
├── extensions.json    # Recommended extensions
└── typescript.json    # Code snippets for common patterns
```

## ⚙️ Key Features

### 🎯 Tasks (Ctrl+Shift+P → Tasks: Run Task)

- **🎮 Start Development** - Runs both client and server in dev mode
- **🏗️ Build Production** - Creates production build
- **🌐 Start Client Only** - Runs webpack dev server only
- **🖥️ Start Server Only** - Runs game server only
- **🧪 Run Tests** - Executes Jest test suite
- **📊 Test Coverage** - Runs tests with coverage report
- **🎨 Format Code** - Formats all code with Prettier
- **🔍 Lint Code** - Checks code with ESLint
- **🗺️ Generate Maps** - Builds game maps using Go generator

### 🐛 Debug Configurations (F5)

- **🚀 Debug Full Game** - Debug both server and client simultaneously
- **🎮 Debug Game Server** - Debug Node.js server with TypeScript support
- **🌐 Debug Client** - Debug in Chrome with source maps
- **🧪 Debug Jest Tests** - Debug test files
- **🧪 Debug Current Test File** - Debug the currently open test file

### 🔧 Editor Settings

- **Auto-format on save** with Prettier
- **Auto-fix ESLint issues** on save
- **Organize imports** automatically
- **TypeScript IntelliSense** enhanced
- **Error highlighting** with Error Lens
- **Git integration** with GitLens
- **Tailwind CSS** IntelliSense for styling

### 📦 Recommended Extensions

The workspace will suggest installing these extensions:

- **TypeScript Nightly** - Latest TypeScript features
- **ESLint** - Code linting and fixing
- **Prettier** - Code formatting
- **Jest** - Test runner integration
- **GitLens** - Enhanced Git capabilities
- **Error Lens** - Inline error display
- **Tailwind CSS IntelliSense** - CSS framework support
- **Thunder Client** - API testing
- **Material Icon Theme** - Better file icons

### 🎮 Code Snippets

Type these prefixes and press Tab:

- `jesttest` - Complete Jest test suite template
- `gameentity` - Game entity class with update/render methods
- `gamestate` - Game state interface with initial values
- `wsmessage` - WebSocket message handler
- `component` - Game component class
- `perf` - Performance measurement wrapper
- `asyncerror` - Async error handling block

## 🎯 Development Workflow

### Starting Development

1. Press `Ctrl+Shift+P`
2. Type "Tasks: Run Task"
3. Select "🎮 Start Development"
4. This starts both client (localhost:8080) and server

### Testing

- **Run all tests**: Task → `🧪 Run Tests`
- **Debug tests**: F5 → `🧪 Debug Jest Tests`
- **Test coverage**: Task → `📊 Test Coverage`

### Building

- **Development build**: Task → `🔧 Build Development`
- **Production build**: Task → `🏗️ Build Production`

### Code Quality

- **Format code**: Task → `🎨 Format Code` (or save file)
- **Lint code**: Task → `🔍 Lint Code`
- **Auto-fix**: Task → `🔧 Lint & Fix`

## 🔥 Pro Tips

1. **Multi-cursor editing**: Hold `Alt` and click to place multiple cursors
2. **Command palette**: `Ctrl+Shift+P` for quick access to all commands
3. **Quick file open**: `Ctrl+P` to quickly open files by name
4. **Symbol search**: `Ctrl+Shift+O` to jump to functions/classes in current file
5. **Global symbol search**: `Ctrl+T` to find symbols across all files
6. **Go to definition**: `F12` or `Ctrl+Click` on any symbol
7. **Find references**: `Shift+F12` to find all uses of a symbol
8. **Rename symbol**: `F2` to rename across all files
9. **Toggle terminal**: `Ctrl+`` (backtick)
10. **Split editor**: `Ctrl+\\` for side-by-side editing

## 🎮 Game-Specific Features

### Map Generation

- Run `🗺️ Generate Maps` task to rebuild game maps
- Maps are generated using Go and automatically formatted

### Performance Testing

- Run `🏃‍♂️ Performance Tests` for game performance benchmarks
- Results help optimize game loops and rendering

### API Environment Switching

- `🚀 Dev with Staging API` - Connect to staging servers
- `🌐 Dev with Production API` - Connect to production servers
- Useful for testing user profiles and purchases

## 🛠️ Troubleshooting

### TypeScript Errors

- Restart TypeScript: `Ctrl+Shift+P` → "TypeScript: Restart TS Server"
- Check `tsconfig.json` for configuration issues

### Jest Not Working

- Ensure Jest extension is installed and enabled
- Check `jest.config.ts` for configuration
- Restart VS Code if needed

### Debugging Issues

- Make sure source maps are enabled in webpack config
- Check port conflicts (server runs on different ports)
- Verify Chrome debugging extensions are enabled

### Performance Issues

- Disable unnecessary extensions
- Increase VS Code memory limit in settings
- Close unused editor tabs

## 📚 Additional Resources

- [OpenFrontIO Documentation](https://github.com/openfrontio/OpenFrontIO)
- [VS Code TypeScript Docs](https://code.visualstudio.com/docs/languages/typescript)
- [Jest Testing Framework](https://jestjs.io/docs/getting-started)
- [Webpack Documentation](https://webpack.js.org/concepts/)

Happy coding! 🎮✨
