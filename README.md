# Skill Bridge - Career Readiness Platform
## Smart India Hackathon Project

*Make your next career move with clarity.*

A human-centered platform that transforms confusing job requirements into clear, personalized action plans for students.

---

## 🎯 Project Vision

Help students move from **uncertainty → focused preparation → confident applications**

For every student asking: *"Am I ready—and what should I learn next?"*

---

## 📋 Core Problem We're Solving

- Students see long job requirement lists but don't know what matters most
- Career preparation feels like random tutorials and scattered certificates
- No clear connection between current skills and role requirements
- Lack of personalized, actionable guidance

---

## 💡 The Skill Bridge Experience

**Discover → Understand → Build → Apply**

1. **Tell us about yourself** - Create profile with skills, CGPA, projects, certifications
2. **Choose a direction** - Browse companies, roles, and eligibility criteria
3. **See your match** - Get transparent readiness estimate vs. role requirements
4. **Get actionable next steps** - Personalized learning path, not generic advice

---

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Python + Flask
- **Database**: PostgreSQL
- **Authentication**: JWT tokens

---

## 📁 Project Structure

```
ACE (Skill Bridge)/
├── frontend/                          # React frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── StudentProfile/        # Profile creation & editing
│   │   │   ├── RoleMatching/          # Role search & discovery
│   │   │   ├── MatchScore/            # Visual match score display
│   │   │   ├── SkillGapAnalysis/      # Gap visualization
│   │   │   ├── RecommendationPlan/    # Learning path recommendations
│   │   │   └── Common/                # Shared components
│   │   ├── pages/
│   │   │   ├── Onboarding.js
│   │   │   ├── Dashboard.js
│   │   │   ├── RoleDetail.js
│   │   │   └── LearningPath.js
│   │   ├── services/
│   │   │   └── api.js                 # API calls
│   │   └── App.js
│   ├── package.json
│   └── README.md
│
├── backend/                           # Flask backend
│   ├── app.py
│   ├── requirements.txt
│   ├── config.py
│   ├── models/
│   │   ├── student.py                 # Student profile model
│   │   ├── company.py                 # Company & role model
│   │   ├── skill.py                   # Skill model
│   │   └── recommendation.py          # Learning path model
│   ├── routes/
│   │   ├── auth.py                    # Authentication
│   │   ├── student.py                 # Student profile endpoints
│   │   ├── roles.py                   # Role search endpoints
│   │   ├── matching.py                # Matching algorithm
│   │   └── recommendations.py         # Learning path endpoints
│   ├── services/
│   │   ├── match_engine.py            # Core matching logic
│   │   ├── gap_analyzer.py            # Skill gap analysis
│   │   └── path_generator.py          # Learning path generation
│   ├── utils/
│   │   └── helpers.py
│   └── README.md
│
├── database/
│   ├── schema.sql                     # PostgreSQL schema
│   └── seed_data.sql                  # Sample data
│
├── docs/
│   ├── SETUP.md                       # Setup instructions
│   ├── ARCHITECTURE.md                # System architecture
│   ├── API.md                         # API documentation
│   ├── ALGORITHM.md                   # Matching algorithm explanation
│   └── DATABASE.md                    # Database design
│
├── .gitignore
└── README.md
```

---

## 🚀 Key Features (MVP - Hackathon)

### 1. Student Onboarding & Profile
- [ ] Student registration with email/password
- [ ] Profile creation: Branch, CGPA, programming languages, skills, projects, certifications
- [ ] Profile editing and updates
- [ ] Profile visualization (strengths dashboard)

### 2. Company & Role Management
- [ ] Admin panel to add companies
- [ ] Role creation with requirements (skills, CGPA, eligibility)
- [ ] Selection process details
- [ ] Role browsing by category/company

### 3. Profile-to-Role Matching
- [ ] Match score calculation (0-100%)
- [ ] Breakdown of matching criteria
- [ ] Visual match indicator
- [ ] "Already have" vs "Need to strengthen" categorization

### 4. Skill-Gap Analysis
- [ ] Identify missing skills
- [ ] Prioritize gaps based on role importance
- [ ] Visual gap representation
- [ ] Difficulty/learning time estimation

### 5. Personalized Learning Recommendations
- [ ] Structured learning path suggestions
- [ ] Project recommendations
- [ ] Practice problem suggestions
- [ ] Milestone tracking

### 6. Dashboard & Tracking
- [ ] Student dashboard with progress
- [ ] Saved roles tracking
- [ ] Learning path progress
- [ ] Success signals monitoring

---

## 📊 Success Metrics (Hackathon Goals)

| Metric | Definition |
|--------|-----------|
| **Clarity** | Can a student explain why a role matches their profile? |
| **Actionability** | Can the student identify the first skill/project to work on? |
| **Trust** | Does transparent explanation feel more useful than unexplained score? |
| **Momentum** | Does the plan make the student feel confident about next steps? |

---

## 🧠 Core Algorithm: Matching Engine

```
Match Score = (Weighted Skills Match × 0.4) 
            + (Academic Match × 0.3) 
            + (Experience Match × 0.2) 
            + (Project Match × 0.1)

Result: 0-100% readiness estimate + detailed breakdown
```

---

## 📅 Development Timeline

**Week 1-2**: 
- Backend setup + Database schema
- Student authentication & profile endpoints
- Basic role management

**Week 2-3**:
- Frontend: Onboarding & profile creation
- Role matching algorithm
- Match score calculation

**Week 3-4**:
- Skill-gap analysis visualization
- Learning path recommendation engine
- Dashboard & tracking

**Week 4+**:
- Testing & refinement
- Deployment preparation
- Demo & presentation

---

## 👥 Team: ACE (6 Members)

| Role | Member |
|------|--------|
| Project Lead | - |
| Frontend Lead | - |
| Frontend Dev | - |
| Backend Lead | - |
| Backend Dev | - |
| Database/DevOps | - |

---

## 🔄 Development Workflow

```bash
# Create feature branch
git checkout -b feature/student-profile

# Make changes and commit
git commit -m "Add student profile creation"

# Push to GitHub
git push origin feature/student-profile

# Create Pull Request for review
# After approval, merge to main
```

---

## 📚 Learning Resources

- [Flask Documentation](https://flask.palletsprojects.com/)
- [React Documentation](https://react.dev/)
- [PostgreSQL Guide](https://www.postgresql.org/docs/)
- [Matching Algorithms](https://en.wikipedia.org/wiki/Matching_(graph_theory))

---

## 🤝 Next Steps

1. **Review this structure** with your team
2. **Assign roles** - Who handles what?
3. **Set up local environment** - See [SETUP.md](docs/SETUP.md)
4. **Start with backend** - Database schema first
5. **Build API endpoints** - Student & role management
6. **Create frontend components** - Profile, matching, recommendations

---

**Let's build clarity into career preparation! 🚀**
