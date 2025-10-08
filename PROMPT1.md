**Prompt:**
“Act as a senior software architect specializing in Python and Flask. I need to build an AI-powered multi-user blogging platform called **‘BlogForge’**. Based on the following requirements, please propose a complete project structure and a high-level implementation plan.

**Requirements:**

**Tech Stack:**

* Flask backend (Python)
* SQLite for local persistence using SQLAlchemy ORM
* TailwindCSS for a responsive frontend UI
* Google OAuth 2.0 authentication via Authlib
* Integration with LLM APIs (OpenAI or Gemini) for AI repurposing features

**Core Features:**

* User authentication using Google OAuth
* CRUD operations for blog posts, drafts, and tags
* AI-powered content tools:

  * Convert blog to LinkedIn post
  * Convert blog to Twitter thread
  * Generate blog summaries and tags
* Markdown-based editor with live preview

**Architecture:**

* Modular Flask Blueprints (auth, posts, ai, main)
* Use Jinja2 templates styled with TailwindCSS
* REST endpoints for AI actions
* Organized static and templates directories

**Security:**

* Protect all user routes and post endpoints by session authentication
* CSRF protection and rate limiting for AI endpoints

Please output:

1. A clear **project directory structure**
2. The key **Flask Blueprints and routes**
3. Suggested **database models** (Users, Posts, SocialPosts, Tags)
4. A short summary of how AI repurposing integrates into the architecture.”
