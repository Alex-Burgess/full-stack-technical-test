# Full Stack Technical Test

## The Challenge
Build a modern events platform that solves common challenges faced by organizations managing events in **exactly 1 hour**.

This test evaluates your ability to:
- Leverage AI tools effectively for rapid development
- Solve ambiguous requirements with creative solutions
- Build full-stack functionality under time constraints
- Demonstrate modern frontend engineering skills

**Good luck! Remember: we're evaluating your problem-solving approach and AI collaboration skills, not perfection. Use your best judgment and document your assumptions** 🚀

## Before You Start

### Time & Tracking
- **Implementation time:** 1 hour (tracked via git commits)
- **Documentation time:** Additional time allowed for README updates
- **Honesty policy:** You can read requirements beforehand, but implement within 1 hour

### Technical Requirements
- **Frontend:** React (required) + your choice of other tools
- **AI Tools:** Any models/assistants allowed and highly encouraged
- **API:** Lightweight API provided with shared API key
- **Deployment:** Any platform (API runs on AWS)

### Git Timestamp
```bash
1. Fork this repository
2. First commit: "START: Beginning 1-hour test" 
3. Work for exactly 1 hour with frequent commits
4. Final commit: "SUBMISSION: 1-hour complete"
```


## 📋 Core Requirements (Required)

### Must Have:
1. **Events listing page** with basic filtering and search
2. **Event detail pages** with registration functionality
3. **Responsive design** for mobile and desktop
4. **Working deployment** with shareable URL

## 🚀 Bonus Features (Optional)

**Quality over quantity** - pick one bonus feature that interests you most:

### 📝 Dynamic Event Categories & Content
- Event categories with configurable descriptions, colors, icons
- Marketing copy and promotional banners managed separately from code
- Demonstrate separation of developer-defined structure vs content-managed data
- Show how non-technical staff could manage this content

### 🎯 Event Capacity & Waitlists
- Events have maximum capacity (some are full)
- Users can join waitlists for full events
- Show capacity status (Available/Few spots left/Full/Waitlist)
- May require extending the provided API

### 💾 My Events Feature
- Track events that users have registered for
- **Challenge:** No user account system exists - be creative!
- Consider localStorage, email lookup, session tokens, or other approaches
- Handle edge cases (browser clearing, multiple devices, etc.)


## 🛠 What's Provided

### API Base URL
```
https://x15zoj9on9.execute-api.us-east-1.amazonaws.com/prod/events
```

### API Endpoints
- `GET /events` - List all events with filtering
- `GET /events/:id` - Get event details
- `POST /events/:id/register` - Register for an event

## API Documentation

The complete API specification is available in OpenAPI 3.0 format: [openapi.yaml](https://github.com/HultTechnology/full-stack-tech-test-backend/blob/main/openapi.yaml)

**View the interactive documentation:**
1. Go to [Swagger Editor](https://editor.swagger.io/)
2. Copy the contents of [openapi.yaml](https://github.com/HultTechnology/full-stack-tech-test-backend/blob/main/openapi.yaml)
3. Paste into the editor to see interactive API documentation

### Sample Data
The API includes 20+ sample events with:
- Different dates and times
- Various categories and types
- Mix of online and physical locations
- Rich content for testing different scenarios

### API Code
See [full-stack-tech-test-backend](https://github.com/HultTechnology/full-stack-tech-test-backend)


## 📦 Deliverables

### Required:
- **GitHub repository** (this fork) with your solution
- **Working deployed URL** 
- **Updated README** (below) documenting your approach

### Update This README:

#### 🔗 Deployed URL
<!-- Add your deployed URL here -->
**Live Demo:** [Your deployed URL here]

#### ⚡ My Approach

**Technology Choices:**
<!-- List your tech stack and why you chose it -->

**AI Tool Usage:**
<!-- Document how you used AI tools and what they helped with -->

**Bonus Feature (if implemented):**
<!-- Which bonus feature you chose and how you implemented it -->

**Key Design Decisions:**
<!-- Explain any important architectural or UX decisions -->

#### 🚀 Getting Started
<!-- Add setup instructions for running locally -->
```bash
# Installation
npm install

# Development
npm run dev

# Build
npm run build
```

