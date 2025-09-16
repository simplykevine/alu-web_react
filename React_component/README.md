# React Component Development Module

## Learning Objectives
By the end of this module, you will be able to:
- Create both functional and class components
- Use props and implement PropTypes validation
- Handle events and user interactions
- Implement lifecycle methods and hooks
- Write comprehensive tests with Jest and Enzyme
- Build a complete dashboard application

## Tasks Overview

### Task 0: Basic Components
- Introduction to React components
- JSX syntax and component structure
- Basic rendering patterns

### Task 1: Props and PropTypes
- Passing data between components
- Property validation with PropTypes
- Default props implementation

### Task 2: Event Handling
- User interaction patterns
- Event delegation and handling
- Form controls and inputs

### Task 3: Testing Components
- Jest test runner setup
- Enzyme for component testing
- Snapshot testing strategies

### Task 4: Conditional Rendering
- Dynamic component rendering
- State-based UI updates
- Component composition patterns

### Task 5: Complete Dashboard Application ⭐
**Featured Project**: Full-featured React dashboard with:
- Authentication system
- Notification management
- Course listing functionality
- Header, footer, and navigation
- HOC (Higher-Order Component) patterns
- Comprehensive test coverage (45 tests)

## Quick Start

### Running the Main Dashboard (Task 5)
```bash
cd task_5/dashboard
npm install
npm start          # Development server
npm test           # Run test suite
npm run build      # Production build
```

### Development Workflow
1. Navigate to specific task directory
2. Install dependencies: `npm install`
3. Start development: `npm start`
4. Run tests: `npm test`
5. Build for production: `npm run build`

## Key Features Implemented

### Dashboard Application Features
- **Authentication Flow**: Login/logout functionality
- **Notification System**: Real-time notifications with priority levels
- **Course Management**: Display and manage course listings
- **Responsive Layout**: Header, body, and footer components
- **HOC Pattern**: WithLogging higher-order component
- **Keyboard Shortcuts**: Ctrl+H for logout
- **PropTypes Validation**: Type safety throughout

### Testing Coverage
- Component rendering tests
- Props validation tests
- Event handling verification
- Lifecycle method testing
- HOC functionality tests
- Utility function tests

## Architecture Patterns

### Component Structure
```
src/
├── App/                 # Main application component
├── Header/              # Site header with user info
├── Footer/              # Site footer
├── Login/               # Authentication forms
├── Notifications/       # Notification system
├── CourseList/          # Course display components
├── BodySection/         # Layout components
├── HOC/                 # Higher-order components
└── utils/               # Utility functions
```

### State Management
- Class component state management
- Props drilling patterns
- Event handling and state updates
- Component lifecycle utilization

## Best Practices Demonstrated
- Proper component composition
- Event handling patterns
- Testing methodology
- Code organization
- PropTypes usage
- Performance considerations
