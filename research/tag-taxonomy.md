# Topic Tag Taxonomy

Generated: 2026-02-09 18:54:59

## Overview

This document defines the standardized topic tag system for the Papers library.

## Tag Categories

### 1. Exposure_* (Adverse Experiences)
Tags for types of adverse childhood experiences and exposures:

- **Exposure_ChildhoodAbuse**: General childhood abuse (emotional, physical, sexual)
- **Exposure_ChildSexualAbuse**: Specifically sexual abuse
- **Exposure_ChildPhysicalAbuse**: Specifically physical abuse
- **Exposure_ChildEmotionalAbuse**: Specifically emotional abuse
- **Exposure_Trauma**: General trauma exposure
- **Exposure_IntimatePartnerViolence**: Dating/intimate partner violence

### 2. Mechanism_* (Psychological Mechanisms)
Tags for mediators and moderators linking exposure to outcomes:

- **Mechanism_Attachment**: Attachment styles, attachment anxiety/avoidance
- **Mechanism_EmotionRegulation**: Emotion dysregulation, affect regulation
- **Mechanism_Mentalizing**: Mentalizing, reflective functioning
- **Mechanism_EmotionalClarity**: Emotional awareness, clarity of emotions
- **Mechanism_SelfEfficacy**: Self-efficacy, self-concept
- **Mechanism_Resilience**: Resilience factors
- **Mechanism_Coping**: Coping strategies
- **Mechanism_Mindfulness**: Mindfulness-based mechanisms
- **Mechanism_CognitiveDistortions**: Cognitive biases, distortions
- **Mechanism_Shame**: Shame, guilt, self-blame

### 3. Outcome_* (Mental Health Outcomes)
Tags for psychological and behavioral outcomes:

- **Outcome_Depression**: Depressive symptoms, MDD
- **Outcome_Anxiety**: Anxiety symptoms, GAD
- **Outcome_PTSD**: PTSD, Complex PTSD
- **Outcome_BPD**: Borderline Personality Disorder
- **Outcome_Suicide**: Suicidal ideation, attempts
- **Outcome_Psychopathology**: General psychopathology
- **Outcome_Wellbeing**: Psychological well-being
- **Outcome_InterpersonalProblems**: Relationship difficulties

### 4. Context_* (Population & Setting)
Tags for study context and population:

- **Context_EmergingAdulthood**: Emerging adults (18-29)
- **Context_Adolescence**: Adolescents
- **Context_CollegeStudents**: College/university students
- **Context_DigitalTherapeutics**: Digital mental health, AI, LLMs

### 5. Project_* (Research Projects)
Tags for specific research projects:

- **Project_DeepResearch**: DeepResearch project papers

## Tag Distribution

Current tag usage across the library:

- **Exposure_ChildhoodAbuse**: 59 papers
- **Mechanism_Attachment**: 58 papers
- **Project_DeepResearch**: 14 papers
- **Mechanism_EmotionRegulation**: 12 papers
- **Outcome_Anxiety**: 11 papers
- **Outcome_Depression**: 11 papers
- **Outcome_BPD**: 8 papers
- **Context_DigitalTherapeutics**: 4 papers
- **Mechanism_Mentalizing**: 4 papers
- **Outcome_PTSD**: 4 papers
- **Context_EmergingAdulthood**: 2 papers
- **Outcome_Psychopathology**: 2 papers
- **Exposure_IntimatePartnerViolence**: 1 papers
- **Exposure_Trauma**: 1 papers
- **Mechanism_Mindfulness**: 1 papers
- **Mechanism_Resilience**: 1 papers
- **Mechanism_SelfEfficacy**: 1 papers
- **Outcome_Wellbeing**: 1 papers

## Usage Guidelines

### Tagging Principles

1. **Multiple tags**: Papers can have multiple tags from different categories
   - Example: `Exposure_ChildhoodAbuse, Mechanism_EmotionRegulation, Outcome_Depression`

2. **Specificity**: Use most specific tag available
   - Prefer `Exposure_ChildSexualAbuse` over general `Exposure_ChildhoodAbuse` if specific

3. **Required categories**: Try to tag with at least:
   - One Exposure_* tag (what's the risk factor?)
   - One Mechanism_* tag (what's the process?)
   - One Outcome_* tag (what's the result?)

4. **Context tags**: Add Context_* tags for population/setting when relevant

### Examples

**Paper**: "Emotion regulation mediates childhood abuse and depression"
- Tags: `Exposure_ChildhoodAbuse, Mechanism_EmotionRegulation, Outcome_Depression`

**Paper**: "Attachment anxiety in college students after trauma"
- Tags: `Exposure_Trauma, Mechanism_Attachment, Outcome_Anxiety, Context_CollegeStudents`

**Paper**: "AI-based therapy for PTSD"
- Tags: `Context_DigitalTherapeutics, Outcome_PTSD`

## Migration from Old Tags

Old tag format → New format mapping:

- `"Attachment, Child Abuse"` → `"Exposure_ChildhoodAbuse, Mechanism_Attachment"`
- `"DeepResearch:Depression"` → `"Project_DeepResearch, Outcome_Depression"`
- `"PTSD"` → `"Outcome_PTSD"`
- `"DTx"` → `"Context_DigitalTherapeutics"`
- `"Temporary"` → Inferred from paper title/content

---

**Note**: Tags starting with `REVIEW_` indicate tags that need manual review and classification.
