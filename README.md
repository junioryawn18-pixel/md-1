# md-1
My GitHub profile README: aspiring software developer learning full-stack web development.
# Commit 1: Name and intro
cat > README.md << 'EOF'
# Yaw Adomako

## About Me

👋 Hi, I'm Yaw Adomako.

I am an aspiring software developer who enjoys building practical solutions to real-world problems. I am currently learning full-stack web development and am eager to keep growing through hands-on projects, collaboration, and new opportunities.
EOF
git add README.md
git commit -m "Add name and brief introduction"

# Commit 2: Technical skills
cat >> README.md << 'EOF'

## 🛠️ Technical Skills

**Languages:** Python · JavaScript · HTML · CSS · SQL

**Frameworks & Libraries:** React · Node.js · Flask

**Tools:** Git · GitHub · VS Code · Terminal
EOF
git add README.md
git commit -m "Add technical skills section"

# Commit 3: Learning goals and projects
cat >> README.md << 'EOF'

## 🌱 What I'm Working On

**Currently learning:**

- Building responsive websites with HTML, CSS, and JavaScript
- Version control and collaborative workflows with Git
- Data structures and algorithms

**Projects:**

- 🔹 **Personal portfolio website** – A responsive site to showcase my work (in progress)
- 🔹 **This profile README** – My first professional GitHub presence

**Goals:**

- Build and deploy a full-stack web app
- Contribute to an open source project
- Land an internship or junior developer role
EOF
git add README.md
git commit -m "Add current learning goals and projects"

# Commit 4: Contact info
cat >> README.md << 'EOF'

## 📫 Let's Connect

- ✉️ Email: [junioryawn18@gmail.com](mailto:junioryawn18@gmail.com)
- 💼 LinkedIn: [Yaw Adomako](https://linkedin.com/in/YOUR-HANDLE)
- 🌐 Portfolio: coming soon
EOF
git add README.md
git commit -m "Add contact information and links"

# Commit 5: Polish and personality
cat >> README.md << 'EOF'

## ✨ A Little More About Me

- 🎧 I code best with good music and a big cup of coffee
- 📚 Always learning something new
- ⚽ Outside of coding: sports, music, and spending time with friends and family
- 💡 Fun fact: I'm building this profile as part of my journey into software development

> "Make it work, make it right, make it fast." – Kent Beck
EOF
git add README.md
git commit -m "Polish formatting and add personal touches"

# Check history and push
git log --oneline
git push
