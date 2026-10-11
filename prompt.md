Act as an expert Open-Source Developer and GitHub Profile Designer. Generate a production-ready, visually stunning, dark-mode-optimized GitHub Profile `README.md` based strictly on the user details provided below.

---

### 🎨 DESIGN & STRUCTURE REQUIREMENTS:

1. **Header & Hero Section**:
   - Centered alignment (`<div align="center">`).
   - Greeting with waving hand GIF (`https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif`).
   - Full Name, Education/Title, and Focus areas.
   - Dynamic Typing SVG banner (`readme-typing-svg.demolab.com`) containing 4 rotating phrases customized to the user's domain (color: `38BDF8`, font: `Fira Code`).
   - Top social badges (`style=for-the-badge`): Email, LinkedIn, GitHub, Profile Views Counter (`komarev.com`), LeetCode, and GeeksforGeeks / other platforms.

2. **About Me**:
   - A clean `yaml` syntax block summarizing: name, education, focus_areas, current_status, and passions.
   - Bulleted highlights with emojis covering background, key projects, learning focus, and discussion topics.

3. **Tech Stack & Categorized Badges**:
   - Grouped into neat categories (e.g., Languages & Core, Frameworks & Libraries, Tools & DevOps).
   - Use official shields.io badges (`style=for-the-badge`, with official brand icons, colors, and white/black logos).

4. **Featured Projects Table**:
   - Clean Markdown table (`| Project | Description | Tech Stack |`).
   - Project links with descriptive emojis and backtick tags for tech stacks.

5. **Expandable Accreditations & Milestones**:
   - Collapsible `<details><summary>` element with key milestones and achievements.

6. **GitHub Contribution Snake**:
   - Dual-theme or dark-mode snake animation SVG pointing to `https://raw.githubusercontent.com/<GITHUB_USERNAME>/<GITHUB_USERNAME>/output/github-contribution-grid-snake-dark.svg`.

7. **GitHub Analytics & Productivity**:
   - 2x2 grid using HTML `<table>` for perfect alignment:
     - Card 1: `github-readme-stats` (theme: `tokyonight`, `hide_border=true`, `bg_color=0d1117`, `title_color=38bdf8`).
     - Card 2: Top Languages (`github-readme-stats/api/top-langs/` with compact layout).
     - Card 3: Profile Details (`github-profile-summary-cards`).
     - Card 4: Productive Time (`github-profile-summary-cards` with user's UTC offset).
   - Full-width Streak Stats (`streak-stats.demolab.com`).

8. **Competitive Programming / Problem Solving**:
   - LeetCode Card (`https://leetcard.jacoblin.cool/<LEETCODE_USERNAME>?theme=dark&font=Fira%20Code`).
   - GeeksforGeeks Card (`https://gfgstatscard.vercel.app/<GFG_USERNAME>?theme=dark`) (or Codeforces/HackerRank).

9. **Dynamic Activity & Daily Quote**:
   - GitHub Actions automated activity placeholder comments (`<!-- RECENT_ACTIVITY:start -->` and `<!-- RECENT_ACTIVITY:end -->`).
   - Daily Programming Quote (`https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight`).

10. **Footer / Get In Touch**:
    - Centered contact section with `style=flat-square` badges linking to social profiles.

---

### 📝 USER INPUT DATA (Fill in your details below):

- **Full Name**: [e.g., Aditya Kumar Singh]
- **Headline / Subtitle**: [e.g., Computer Science & Engineering • AI & Machine Learning Enthusiast]
- **Typing Banner Phrases (4 phrases)**:
  1. [e.g., Passionate about Artificial Intelligence]
  2. [e.g., Building Autonomous AI Assistants]
  3. [e.g., Developing Offline Legal Tech & Automation]
  4. [e.g., Crafting Modern Full-Stack & IoT Solutions]
- **Email**: [e.g., yourname@gmail.com]
- **GitHub Username & Profile URL**: [e.g., USERNAME | https://github.com/USERNAME]
- **LinkedIn Profile URL**: [e.g., https://www.linkedin.com/in/USERNAME/]
- **LeetCode Username & URL**: [e.g., USERNAME | https://leetcode.com/u/USERNAME/]
- **GeeksforGeeks / Coding Profile URL**: [e.g., USERNAME | https://www.geeksforgeeks.org/profile/USERNAME]
- **Timezone UTC Offset**: [e.g., 5.5 for IST, 0 for UTC, -5 for EST]

- **About Me Details**:
  - Education / Institution: [e.g., Techno India University]
  - Key focus areas: [e.g., AI/ML, Full-Stack, IoT]
  - Current status: [e.g., Building AI assistants]
  - Key projects mentioned in bio: [e.g., Project A, Project B]

- **Tech Stack**:
  - Languages: [e.g., Python, JavaScript, TypeScript, C, C++, HTML5, CSS3]
  - Frameworks & Libraries: [e.g., PyTorch, TensorFlow, OpenCV, FastAPI, Flask, Node.js, Express.js]
  - Tools & Platforms: [e.g., Git, GitHub, VS Code, Docker, Linux, Postman, MongoDB, PostgreSQL]

- **Featured Projects (3 to 6 projects)**:
  1. Name: [Project Name] | URL: [Repo URL] | Description: [1 sentence] | Tech: [e.g., Python, NLP, Ollama]
  2. Name: [Project Name] | URL: [Repo URL] | Description: [1 sentence] | Tech: [e.g., Python, Speech-to-Text]
  3. Name: [Project Name] | URL: [Repo URL] | Description: [1 sentence] | Tech: [e.g., React, Node.js]

---

### Output Instruction:
Output ONLY the raw GitHub-flavored Markdown file content inside a single markdown code block. Ensure all URLs and image parameters are properly encoded and functional.
