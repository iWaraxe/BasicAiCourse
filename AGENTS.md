# AI Course Update Workflow

## Course Structure Requirements

### Slide Format Rules
1. **Each slide (##### level) must contain NO MORE THAN ONE of each section type:**
   - One `###### SCRIPT` section
   - One `###### VISUAL` section  
   - One `###### NOTES` section
   - One `###### DEMONSTRATION` section (optional)
   - One `###### ACTIVITY` section (optional)
   - One `###### REFLECTION` section (optional)
   - One `###### LINKS` section (optional)
   - One `###### ARCHIVE` section (optional)

2. **Slide boundaries are marked by:**
   - Next slide header (`##### [seq:XXX]`)
   - OR section divider (`---`)

### Course Hierarchy
```
# Course name
## Lecture X
### Section
#### Subsection  
##### [seq:XXX] Slide title
###### SCRIPT
###### VISUAL
###### NOTES
###### LINKS
###### DEMONSTRATION (optional)
###### ACTIVITY (optional)
###### REFLECTION (optional)
###### ARCHIVE (optional)
---
```

### Slide Structure Components (Updated)

- **SCRIPT**: Conversational narrative (1-2 minutes speaking time)
- **VISUAL**: Slide design description with engagement elements
- **NOTES**: Discussion prompts, fun facts, real-world connections (text only)
- **LINKS**: Relevant URLs and references from source materials
- **DEMONSTRATION**: Interactive AI experiments with expected outcomes
- **ACTIVITY**: Hands-on student exercises or games
- **REFLECTION**: Critical thinking questions for deeper analysis
- **ARCHIVE**: Removed content with deletion rationale and date

## Course Update Workflow - Keeping Content Current

### Overview
This workflow ensures the course stays relevant with the latest developments while maintaining quality and preventing content bloat. Updates should be strategic, replacing outdated content rather than just adding new material.

### 1. Content Analysis Strategy

#### Step 1: Categorize New Information
Analyze incoming materials and categorize by:
- **Technology Updates**: New models, capabilities, tools
- **Bias/Ethics Cases**: New examples of AI bias or ethical dilemmas
- **Failures/Errors**: Recent AI mistakes or limitations
- **Success Stories**: Positive AI applications
- **Regulatory Changes**: New laws or guidelines
- **Cultural Shifts**: Changes in how society views/uses AI

#### Step 2: Map to Existing Content
Identify where updates belong:
- New AI models → Lecture 1 (Introduction to AI)
- Model capabilities → Lecture 2 (Practical Applications)
- Advanced features → Lecture 3 (Advanced Features)
- Specialized tools → Lecture 4 (Expanding Horizons)
- Ethical dilemmas → Throughout course (Ethics sections)
- Future trends → Lecture 4 (Future sections)

### 2. Create Update Branch
```bash
git checkout -b descriptive-update-name
```

### 3. Update Implementation Guidelines

#### Content Replacement Strategy
**DO:**
- Replace outdated examples with new ones
- Update statistics and facts
- Refresh pop culture references
- Modernize demonstrations
- Streamline verbose sections
- Move removed content to ARCHIVE section
- Add URLs to LINKS section
- Keep NOTES text-only

**DON'T:**
- Just append new content to existing
- Delete information permanently (use ARCHIVE)
- Let any lecture exceed 1.5 hours
- Add complexity beyond target level
- Create new sections without removing old
- Put links in NOTES (use LINKS section)

### 4. Integration Strategy
- **DO NOT** duplicate existing sections
- **DO NOT** add multiple SCRIPT/VISUAL/NOTES sections to one slide
- **MERGE** new content into existing sections where appropriate
- **MAINTAIN** the narrative flow and teaching structure

### 5. Practical Update Examples

#### Example 1: New AI Model Released
**Material**: "DeepSeek-R1-0528 released with superior coding performance"
**Action**:
- Update Lecture 1, slide [seq:070] "Open-Source Models"
- Replace older model examples with DeepSeek-R1-0528
- Add coding superiority to capabilities
- Move old model content to ARCHIVE with rationale
- Add source URL to LINKS section

#### Example 2: Major AI Ethics Incident
**Material**: "Anthropic CEO warns of 50% job displacement"
**Action**:
- Update Lecture 1, slide [seq:280] "Ethical AI"
- Replace older example with this current warning
- Update DEMONSTRATION with new discussion exercise
- Move old example to ARCHIVE with explanation
- Add article URL to LINKS section

### 6. Review Process
1. Create PR with clear description of changes
2. Ensure no duplicate section headers within slides
3. Verify slide structure compliance
4. Address review feedback promptly

### 7. Common Integration Points
- **New AI models** → Lecture 1, relevant model sections
- **Model capabilities** → Lecture 2, practical application sections
- **Advanced features** → Lecture 3, tool-specific sections
- **API/Tool updates** → Lecture 4, specialized tools
- **Ethics cases** → Throughout course, ethics sections
- **Resources** → End of each lecture in Learning Resources

### 8. Language Version Management

**IMPORTANT**: Updates are made ONLY to English version. Other language versions are updated separately when course delivery is ordered for specific countries.

Process:
1. All updates go to English lectures only
2. Document which slides/sections were updated
3. When course is ordered for specific country:
   - User will manually transfer changes to target language
   - Apply cultural localization during transfer
   - Ensure demonstrations work in target region

## Important Notes
- Each lecture is approximately 1.5 hours of content
- Updates should enhance, not bloat the course
- Maintain consistent tone and teaching style
- Test demonstrations before including them
- Always use ARCHIVE for removed content
- Keep URLs in LINKS section, not NOTES