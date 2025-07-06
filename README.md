<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=28&pause=1000&color=00FF41&center=true&vCenter=true&width=435&lines=Welcome+to+my+terminal;Type+%22help%22+to+get+started" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Status-Available%20for%20Hire-00FF41?style=for-the-badge&logo=terminal" alt="Status" />
  <img src="https://img.shields.io/badge/Location-Earth%2C%20Milky%20Way-00FF41?style=for-the-badge&logo=location" alt="Location" />
  <img src="https://img.shields.io/badge/Timezone-UTC%2B0-00FF41?style=for-the-badge&logo=clock" alt="Timezone" />
</div>

---

## 💻 Terminal Commands

<details>
<summary><b>📁 ls - List Skills & Technologies</b></summary>

```bash
$ ls -la
drwxr-xr-x  2 user  staff   4096 Jan 01 00:00 .
drwxr-xr-x  2 user  staff   4096 Jan 01 00:00 ..
-rw-r--r--  1 user  staff   1024 Jan 01 00:00 frontend.md
-rw-r--r--  1 user  staff   1024 Jan 01 00:00 backend.md
-rw-r--r--  1 user  staff   1024 Jan 01 00:00 devops.md
-rw-r--r--  1 user  staff   1024 Jan 01 00:00 tools.md

$ cat frontend.md
📱 Frontend Development
├── React.js & Next.js
├── TypeScript & JavaScript
├── HTML5 & CSS3
├── Tailwind CSS & Bootstrap
├── Redux & Context API
└── Responsive Design

$ cat backend.md
⚙️ Backend Development
├── Node.js & Express.js & Nest.js
├── PostgreSQL & MongoDB & SQLite
├── RESTful APIs & GraphQL
└── Microservices Architecture

$ cat devops.md
🐳 DevOps & Cloud
├── Docker & Kubernetes
├── CI/CD Pipelines
├── Monitoring & Logging
└── Infrastructure as Code

$ cat tools.md
🛠️ Tools & Technologies
├── Git & GitHub
├── VS Code & Cursor
├── Postman & Insomnia
├── Figma
├── Jira
└── Slack
```

</details>

<details>
<summary><b>🎯 whoami - About Me</b></summary>

```bash
$ whoami
user@retro-terminal:~$ whoami

╔══════════════════════════════════════════════════════════════╗
║                    SYSTEM INFORMATION                        ║
╠══════════════════════════════════════════════════════════════╣
║ Username:     Monulph                                        ║
║ Role:         Front-End Engineer                             ║
║ Experience:   5+ Years                                       ║
║ Specialties:  Web Development                                ║
║ Location:     🌍 Remote / Worldwide                          ║
║ Status:       🔴 Not Looking for a Job                       ║
╚══════════════════════════════════════════════════════════════╝

$ cat /etc/passwd | grep user
user:x:1000:1000:Passionate Developer, Problem Solver, Tech Enthusiast:/home/user:/bin/bash

$ echo $MOTTO
"Code is poetry, bugs are features, and coffee is life ☕"
```

</details>

<details>
<summary><b>📊 stats - GitHub Statistics</b></summary>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=undefined-art
&show_icons=true&theme=dark&bg_color=0d1117&text_color=00FF41&icon_color=00FF41&title_color=00FF41&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=undefined-art
&theme=dark&background=0d1117&stroke=00FF41&ring=00FF41&fire=00FF41&currStreakNum=00FF41&sideNums=00FF41&currStreakLabel=00FF41&sideLabels=00FF41&dates=00FF41" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=undefined-art
&layout=compact&theme=dark&bg_color=0d1117&text_color=00FF41&title_color=00FF41&hide_border=true" alt="Top Languages" />
</div>

</details>

## 🎮 Interactive Terminal

<div>

```bash
$ help
Available commands:
├── whoami     - Display user information
├── ls         - List skills and technologies
├── stats      - Show GitHub statistics
├── projects   - View recent projects
├── contact    - Get contact information
├── clear      - Clear terminal
└── exit       - Close terminal

$ uptime
System has been up for 5+ years of coding experience

$ fortune
"Good code is its own best documentation." - Steve McConnell
```

</div>

---

## 🎯 Current Status

<div>

```bash
$ systemctl status development
● development.service - Development Environment
   Loaded: loaded (/etc/systemd/system/development.service; enabled)
   Active: active (running) since Mon 2024-01-01 00:00:00 UTC
   Main PID: 1337 (code)
   Status: "Currently working on exciting new projects"
   Tasks: 42 (limit: 4915)
   Memory: 8.2G
   CGroup: /system.slice/development.service
           ├─1337 /usr/bin/code --new-window
           ├─1338 /usr/bin/node server.js
           ├─1339 /usr/bin/python app.py
           └─1340 /usr/bin/docker-compose up

$ journalctl -u development -f
Jan 01 00:00:00 terminal development[1337]: 🚀 Starting new project
Jan 01 00:01:00 terminal development[1338]: 📝 Writing clean, maintainable code
Jan 01 00:02:00 terminal development[1339]: 🐛 Debugging and testing features
Jan 01 00:03:00 terminal development[1340]: ✅ Deploying to production
```

</div>


<details>
<summary><b>💅 View Custom Styling</b></summary>

```css
/* Retro Terminal Theme */
.terminal {
  background-color: #0d1117;
  color: #00ff41;
  font-family: "Fira Code", "Courier New", monospace;
  border: 2px solid #00ff41;
  border-radius: 8px;
  padding: 20px;
  margin: 10px 0;
  box-shadow: 0 0 20px rgba(0, 255, 65, 0.3);
  animation: glow 2s ease-in-out infinite alternate;
}

@keyframes glow {
  from {
    box-shadow: 0 0 20px rgba(0, 255, 65, 0.3);
  }
  to {
    box-shadow: 0 0 30px rgba(0, 255, 65, 0.6);
  }
}

.terminal-header {
  background: linear-gradient(90deg, #00ff41, #00cc33);
  color: #000;
  padding: 10px;
  margin: -20px -20px 20px -20px;
  border-radius: 6px 6px 0 0;
  font-weight: bold;
}

.command {
  color: #00ff41;
  font-weight: bold;
}

.output {
  color: #cccccc;
  margin-left: 20px;
}

.success {
  color: #00ff41;
}

.error {
  color: #ff4444;
}

.warning {
  color: #ffaa00;
}

/* Smooth animations */
.fade-in {
  animation: fadeIn 0.5s ease-in;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.typing {
  overflow: hidden;
  border-right: 2px solid #00ff41;
  white-space: nowrap;
  animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
}

@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

@keyframes blink-caret {
  from,
  to {
    border-color: transparent;
  }
  50% {
    border-color: #00ff41;
  }
}
```

</details>

---

## 🎵 Currently Playing

<div>

```bash
$ mpd status
volume: 85%   repeat: off   random: off   single: off   consume: off
playlist: 1 of 50
current song: Coding Music - Lo-Fi Beats
next song: Deep Focus - Study Session
time: 02:45 / 03:30 (81%)
state: play

$ mpc current
🎵 Coding Music - Lo-Fi Beats
🎧 Perfect for late-night coding sessions
```

```bash
$ echo "Thanks for visiting my terminal! 🖥️"
Thanks for visiting my terminal! 🖥️

$ echo "Feel free to reach out for collaborations! 🤝"
Feel free to reach out for collaborations! 🤝

$ echo "Happy coding! 💻"
Happy coding! 💻

$ exit
Connection closed by foreign host.
```

</div>

---

<div align="center">
  <sub>Made with ❤️ and ☕</sub>
</div>
