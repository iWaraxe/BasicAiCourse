# AI Course Update Workflow

## Course Structure Requirements

### Slide Format Rules
1. **Each slide (##### level) must contain NO MORE THAN ONE of each section type:**
   - One `###### SCRIPT` section
   - One `###### VISUAL` section  
   - One `###### NOTES` section
   - One `###### DEMONSTRATION` section (optional)

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
###### DEMONSTRATION (optional)
---
```

## Update Workflow Process

### 1. Analyze New Content
- Identify which lecture(s) and section(s) the new information belongs to
- Find relevant existing slides that discuss related topics

### 2. Create Update Branch
```bash
git checkout -b descriptive-update-name
```

### 3. Integration Strategy
- **DO NOT** duplicate existing sections
- **DO NOT** add multiple SCRIPT/VISUAL/NOTES sections to one slide
- **MERGE** new content into existing sections where appropriate
- **MAINTAIN** the narrative flow and teaching structure

### 4. Content Updates
When updating with new information (e.g., GPT-4.1 context window):
- Integrate into existing SCRIPT section narrative
- Add new visual elements to existing VISUAL section
- Include references/links in existing NOTES section
- Update DEMONSTRATION if needed to showcase new capabilities

### 5. Review Process
1. Create PR with clear description of changes
2. Ensure no duplicate section headers within slides
3. Verify slide structure compliance
4. Address review feedback promptly

### 6. Common Integration Points
- **Context Window updates** → Lecture 1, seq:100
- **Model capabilities** → Lecture 1, seq:140 (Multimodal AI)
- **API features** → Lecture 4, seq:020
- **Tool features** → Lecture 3, relevant tool section
- **Resources** → End of each lecture in Learning Resources

## Example: GPT-4.1 Update
We successfully updated:
1. Context Window section - merged 1M token info into existing content
2. Multimodal AI - added enhancement note within existing explanation  
3. ChatGPT features - integrated new capability into feature list
4. API Integration - added enterprise use case to existing section
5. Learning Resources - added documentation reference to notes

## Important Notes
- Each lecture is approximately 1.5 hours of content
- Updates should enhance, not bloat the course
- Maintain consistent tone and teaching style
- Test demonstrations before including them