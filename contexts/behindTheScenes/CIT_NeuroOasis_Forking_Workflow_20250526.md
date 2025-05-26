# CIT_NeuroOasis_Forking_Workflow_20250526.md

## 🎯 Project Overview

```
Project: NeuroOasis Repository Forking Strategy
Current Version: v1.0 (Proven Workflow)
Date: 20250526
Status: VALIDATED - Production workflow tested with sailing-tools
Organization: NeuroOasis GitHub Teams ($4/user/month)
```

## 🏆 **VALIDATED WORKFLOW - COMPLETE SUCCESS**

### **Test Case Results: sailing-tools Repository**
- ✅ **Fork Created:** scottloebdev/garden → NeurOasis/sailing-tools
- ✅ **Organization Transfer:** GitHub Teams permissions working
- ✅ **Repository Cleanup:** 742 objects → focused sailing repo
- ✅ **Size Reduction:** 19 items → 7 items (63% reduction)
- ✅ **Production Deploy:** Live at https://github.com/NeurOasis/sailing-tools
- ✅ **Collaboration:** Andrew creates, Scott develops, both contribute

## 🚀 **STEP-BY-STEP FORKING WORKFLOW**

### **Phase 1: Andrew Fork Creation**
**Account:** Andrew (scottloebdev)
**Location:** Web browser (github.com)

1. **Navigate to:** https://github.com/scottloeb/garden
2. **Click "Fork" button** (top-right)
3. **Repository name:** `[project-name]` (e.g., sailing-tools)
4. **Description:** Brief project description
5. **Create fork:** Creates `scottloebdev/[project-name]`

### **Phase 2: Organization Transfer** 
**Account:** Andrew (scottloebdev)
**Location:** Fork repository settings

1. **Go to:** `scottloebdev/[project-name]`
2. **Settings → General**
3. **Scroll to "Transfer ownership"**
4. **Transfer to:** `NeuroOasis`
5. **Result:** Repository becomes `NeurOasis/[project-name]`

### **Phase 3: Scott Repository Cleanup**
**Account:** Scott (scottloeb)
**Location:** Terminal/command line

```bash
# Navigate to projects directory
cd ~/Library/Mobile\ Documents/com~apple~CloudDocs/github/

# Clone the NeurOasis repository
git clone https://github.com/NeurOasis/[project-name].git
cd [project-name]

# Move project-specific CITs to main contexts
mv personal-contexts-staging/CIT_[ProjectSpecific]*.md contexts/

# Delete non-project CITs from contexts
rm contexts/CIT_[NonProject]*.md

# Delete non-project behind-the-scenes contexts (keep core standards)
rm contexts/behindTheScenes/CIT_GARDEN_*.md
rm contexts/behindTheScenes/CIT_meta-cit-*.md
# Keep: CIT_CoreStandards_20250526.md

# Remove non-project infrastructure
rm -rf experimental-folders-staging/
rm -rf explorer/ gateway/ sunflower/ generated/ module-generators/ neo4j-sample-data/
rm AUDIT_CHECKLIST.md cleanup.sh CONTRIBUTING.md requirements.txt

# Update README for project focus
cat > README.md << 'EOF'
# [Project Name]

Brief project description and purpose.

## Contents
- Project-specific contexts and documentation
- Project-specific tools and utilities

## GARDEN Integration
Part of the GARDEN ecosystem, focused on [specific domain].

## License
MIT License - Seeds to the Wind
EOF

# Commit the transformation
git add .
git commit -m "🎯 TRANSFORM: Convert GARDEN fork to focused [project-name] repository

✅ REMOVED: All non-[project] contexts and infrastructure  
✅ KEPT: [Project] CITs + core standards + essential tools
✅ RESULT: [X]% size reduction
🎯 PURPOSE: Focused [project domain] repository"

# Push to production
git push origin main
```

## 🏢 **NEUROASIS ORGANIZATION SETUP**

### **GitHub Teams Configuration**
- **Plan:** GitHub Teams ($4/user/month)
- **Current Members:** Scott (owner) + Andrew (member)
- **Future:** Dan + Melissa when ready
- **Payment:** Business credit card (expense tracking)
- **Future:** Transfer to corporate entity when incorporated

### **Repository Permissions**
- **Scott (scottloeb):** Organization owner, full admin access
- **Andrew (scottloebdev):** Organization member, developer access
- **Repository Access:** Both can clone, develop, push changes
- **Settings Access:** Only Scott (proper security hierarchy)

## 🎯 **READY FOR FORKING - STAGED PROJECTS**

### **Projects Ready for Individual Repositories:**
1. **Family Tools:** `CIT_Zach_20250523.md` + `CIT_zVisualSchedule-Z_20250515.md`
2. **Coffee Project:** `CIT_blueberryCoffee_20250517.md`
3. **Personal Contexts Collection:** Multiple personal CITs
4. **Future Projects:** Budget NodePad, Action Organizer, etc.

### **Automated Split Criteria (Claude Detection):**
- **🚨 IMMEDIATE SPLIT:** Project knowledge >70% in conversation
- **🔔 SPLIT RECOMMENDATION:** >3 CITs for single non-core project
- **⚠️ PERSONAL CONTEXTS:** Any personal/family-specific content
- **📁 EXPERIMENTAL FOLDERS:** Experimental code >10 files

## 🤖 **CLAUDE AUTOMATION FRAMEWORK**

### **Split Detection Template:**
```
🚨 REPOSITORY SPLIT REQUIRED
Project: [Project Name]
Trigger: [Specific trigger criteria]
Action: Fork to NeurOasis/[project-name]

EXACT COMMANDS:
1. Andrew creates fork: [specific web steps]
2. Transfer to NeurOasis: [specific settings steps]  
3. Scott cleanup: [exact terminal commands with full paths]
```

### **Success Metrics:**
- ✅ **Zero cognitive load:** Users follow exact commands
- ✅ **No path confusion:** Full paths provided for every command
- ✅ **Account clarity:** Explicit account switching instructions
- ✅ **Error prevention:** Verification steps at each phase

## 📊 **STRATEGIC VALIDATION**

### **Option C (Hybrid Approach) - PROVEN SUCCESSFUL:**
- **Core Repository:** `scottloeb/garden` stays lean and focused
- **Active Development:** `NeurOasis/[project-repos]` for focused work
- **Organization Benefits:** Proper collaboration and permissions
- **Scalable:** Template applies to all future projects

### **Business Benefits:**
- **Expense Tracking:** Business credit card for GitHub Teams
- **Collaboration:** Proper permissions and access control
- **Professional Structure:** Organization ready for corporate transfer
- **Cost Effective:** $4/user/month scales with team growth

## 🔄 **NEXT EXECUTION PLAN**

### **Immediate (This Session):**
1. **Document this CIT** in core GARDEN repository
2. **Fork next project:** Family tools or coffee project
3. **Validate template** with second project transformation

### **Short-term (Next Sprint):**
1. **Complete remaining staged projects** forking
2. **Update core GARDEN documentation** with forking workflow
3. **Create Claude automation prompts** for future splits

### **Medium-term (Next Quarter):**
1. **Corporate entity setup** and organization transfer
2. **Dan + Melissa onboarding** to NeuroOasis
3. **Advanced collaboration workflows** and automation

## 🛡️ **Risk Mitigation**

### **Technical Risks:**
- **Repository Bloat:** Automated detection prevents re-accumulation
- **Account Confusion:** Explicit account switching in all instructions
- **Permission Issues:** Organization structure provides clear hierarchy

### **Business Risks:**
- **Cost Management:** Start with 2 seats, scale incrementally
- **Corporate Transfer:** Plan documented for smooth transition
- **Access Control:** Proper security through organization permissions

## 📝 **Version History**

```
20250526: v1.0 - Initial workflow documentation after sailing-tools validation
```

## 🤖 **Note for Claude**

This CIT captures the **complete, validated forking workflow** for GARDEN projects:
- **Every step tested** and proven with sailing-tools repository
- **Exact commands** with full paths for zero confusion
- **Account management** clarity for multi-user workflow
- **Organization structure** supporting professional collaboration

When recommending repository splits:
- Reference this CIT for exact workflow steps
- Provide complete command sequences with full paths
- Specify account requirements for each phase
- Follow the proven template for consistent results

**Current Status:** Workflow validated, template ready for scaling to all staged projects.