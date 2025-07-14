``` yaml
# Mirror OS Systems — Supplementation Protocol Engine (Demo Only, Not for Clinical Use)
# Author: Simon Martin, Founder & Systems Architect
# Version: v1.0 | Platform: Mirror OS Systems
# Details: see 01_projects/supplement_protocols/readme

meta:
  template_type: "EXAMPLE_TEMPLATE"
  active_profile: true
  compliance_locked: true
  real_user_profile: "demo_case_001"
  bot_instruction: |
    ⚠️ Demo profile. Do not use for individual health decisions.

Mirror OS — Supplement Protocol BOT LOGIC

=== INTAKE & CONFIGURATION ===
prompt: |
  👋 Welcome to Mirror OS Protocol Engine.

  To generate an example supplement protocol for professional review, please answer:

  Name (or alias): Alex Carter  
  Age & Gender: 35, Male  
  Main wellness goals: Focus, Energy, Sleep  
  Wake time: 6:30 AM  
  Gym/work schedule: Mon/Wed/Fri, 7:00–8:00 AM (Weightlifting); Tue/Thu, 6:00 PM (Cardio)  
  Known allergies/medications: Gluten sensitivity; no meds  
  Current supplements: None  
  Stack size preference: 7

acknowledgment: |
  Received. Defaults applied for blank fields.
  Protocol example ready for professional review.

=== SUPPLEMENT PROTOCOL GENERATION ===
output_header: |
  Mirror OS — Supplement Protocol Example  
  User: Alex Carter | Age: 35 | Goals: Focus, Energy, Sleep | Stack Limit: 7

references_block: |
  📚 References & Evidence Base
  - Caffeine + L-Theanine: Haskell et al., 2008. Biological Psychology. PMID: 17993239
  - Rhodiola Rosea: Darbinyan et al., 2000. Phytomedicine. PMID: 11081987
  - L-Tyrosine: Jongkees et al., 2015. Psychopharmacology. PMID: 25212136
  - Magnesium Glycinate: de Baaij et al., 2015. Physiological Reviews. PMID: 25540137
  - Zinc: Prasad, 2014. Frontiers in Nutrition. PMID: 25988117
  - Theanine: Unno et al., 2017. Asia Pacific J Clin Nutr. PMID: 29101845

privacy_notice: |
  🔒 Data Privacy Notice
  All user data is processed in accordance with the Mirror OS Privacy Policy.  
  For details, see: [mirroros.super.site/privacy]

protocol_meta:
  protocol_generated_at: "2025-07-14T14:30:00Z"
  protocol_version: "mirror_proto_001.yaml"
  user_id: "ALEXC-35M"
  coach_id: "DEMO"

  For professional use only. Not medical advice.

allergy_block: |
  🚨 Allergy & Contraindication Summary
  Allergy/Contraindication Notice:

  Reported: Gluten sensitivity
  Medications/Other Considerations: None
  Excluded: Any supplements with gluten or cross-contamination risk
  Substitutions: All ingredients are gluten-free

morning_stack: |
  🌞 Morning Stack (Suggested)
  🧠 Caffeine + L-Theanine — 100mg/200mg (7:00 AM, post-breakfast)  
  Phase: Drive  
  Timing: Immediately after breakfast  
  Rationale: Synergistically boosts alertness and reduces caffeine-induced jitters  
  Application: Morning focus, energy for training  
  Short-term potential: Enhanced attention, rapid energy onset  
  Long-term potential: Cognitive resilience, habit formation  
  Mechanism & Insight: Adenosine antagonism and alpha-wave promotion  
  Reference: Haskell et al., 2008  
  Notice: Avoid extra caffeine after 1 PM  
  Goal Link: Focus, Energy  
  Cycle Note: Use on all Drive days

  🧠 Rhodiola Rosea — 200mg (7:15 AM, on Drive days)  
  Phase: Drive  
  Timing: 15 min after morning caffeine  
  Rationale: Adaptogen for stress resilience, supports energy without overstimulation  
  Application: Stressful workdays, gym prep  
  Short-term potential: Reduced fatigue, better stress response  
  Long-term potential: Lower burnout risk  
  Mechanism & Insight: Modulates cortisol and monoamines  
  Reference: Darbinyan et al., 2000  
  Notice: Cycle 5 days on, 2 off  
  Goal Link: Energy  
  Cycle Note: Use only on Drive days

  🧠 L-Tyrosine — 500mg (7:30 AM, with water)  
  Phase: Drive  
  Timing: 30 min before demanding cognitive work  
  Rationale: Dopamine precursor, supports mental stamina  
  Application: Heavy focus blocks, work projects  
  Short-term potential: Improved focus under stress  
  Long-term potential: Resilience to cognitive fatigue  
  Mechanism & Insight: Supports catecholamine synthesis  
  Reference: Jongkees et al., 2015  
  Notice: Skip if thyroid medication present  
  Goal Link: Focus  
  Cycle Note: Use Mon/Wed/Fri

evening_stack: |
  🌙 Evening Stack (Suggested)
  🧠 Magnesium Glycinate — 300mg (8:00 PM, after dinner)  
  Phase: Integrate  
  Timing: 1–2 hours before bed  
  Rationale: Supports sleep quality, muscle recovery  
  Application: Sleep, muscle relaxation  
  Short-term potential: Reduced muscle tension  
  Long-term potential: Improved sleep cycles  
  Mechanism & Insight: NMDA receptor modulation, GABAergic activity  
  Reference: de Baaij et al., 2015  
  Notice: May cause loose stools in excess  
  Goal Link: Sleep, Recovery  
  Cycle Note: Use daily

  🧠 Zinc — 15mg (8:00 PM, after dinner)  
  Phase: Integrate  
  Timing: With magnesium  
  Rationale: Hormonal balance, immune function  
  Application: Recovery, general health  
  Short-term potential: Supports testosterone, immune health  
  Long-term potential: Reduces risk of deficiency  
  Mechanism & Insight: Cofactor for enzymes, modulates neurotransmission  
  Reference: Prasad, 2014  
  Notice: Avoid taking with high-dose calcium  
  Goal Link: Recovery  
  Cycle Note: Use 5 days on, 2 off

  🧠 L-Theanine — 200mg (8:30 PM, before bed)  
  Phase: Integrate  
  Timing: 30 min before bedtime  
  Rationale: Calms mind, improves sleep onset  
  Application: Sleep  
  Short-term potential: Faster sleep onset, less anxiety  
  Long-term potential: Improved sleep quality  
  Mechanism & Insight: Increases alpha brain waves  
  Reference: Unno et al., 2017  
  Notice: No sedative effect—safe for regular use  
  Goal Link: Sleep  
  Cycle Note: Use nightly

excluded_block: |
  🚫 Excluded Substances
  None excluded for this example profile. All ingredients are gluten-free.  
  For updated needs, consult a qualified professional.

goal_mapping: |
  🎯 Goal Mapping
  Focus:  
    - Caffeine + L-Theanine  
    - L-Tyrosine  
  Energy:  
    - Caffeine + L-Theanine  
    - Rhodiola Rosea  
  Sleep:  
    - Magnesium Glycinate  
    - L-Theanine

micro_ritual: |
  🕊️ Micro-Ritual Example
  For coaching clients: Before the AM protocol, take 3 deep breaths and recall your main focus for the week.

weekly_phases: |
  📅 Example Weekly Phase Schedule
  Day       Phase      Notes  
  Monday    🏁 Drive    Weightlifting, intense work  
  Tuesday   🏁 Drive    Cardio, project work  
  Wednesday ⚖️ Balance Recovery, light focus  
  Thursday  🏁 Drive    Weightlifting  
  Friday    ⚖️ Balance Cardio, lighter workload  
  Saturday  🛌 Integrate Rest, deep recovery  
  Sunday    🛌 Integrate Reset, sleep optimization

self_audit: |
  📈 Self-Audit Tracker Example
  Day    Sleep    Mood    Energy    Focus    Notes  
  1                                   
  2                                   
  ...                                 

feedback_loop: |
  🔁 Review & Feedback Loop
  After two weeks, review:

  - Which supplements appeared most useful?
  - Any observed side effects or tolerability issues?
  - Notable shifts in sleep, mood, or recovery?
  - Any new goals or context to consider?

  Share this log with your supervising coach or professional for protocol adjustment.

audit_block: |
  🔒 Protocol Audit Summary
  ✅ Phases Balanced  
  ✅ Stack Size Respected (7)  
  ✅ Allergy/Medication Filters Applied  
  ✅ Cycling/Substitution Rules Enforced  
  ✅ Evidence & Reference Layers Present  
  ✅ Weekly Phase Structure Included  
  ✅ Client Review System Active  
  ✅ Protocol Version: mirror_proto_001.yaml

  Protocol generated as an example for professional review only. Not medical advice.

symbolic_block: |
  🌗 Personalization Example

  Dear Alex,

  This protocol was designed to align with your focus on clarity, sustainable energy, and sleep restoration—while respecting your gluten sensitivity.  
  Each ingredient was selected for evidence, safety, and congruence with your daily rhythm: active mornings, focused work, gentle recovery.  
  Though this is a demonstration, it mirrors the adaptive, thoughtful approach expected from Mirror OS tools in real-world coaching.

  Track your response. You may find that combinations (e.g., Magnesium + Theanine at night) enhance not only sleep, but resilience and mood.  
  Share with your coach after two weeks for tailored adjustments.

  With alignment and care,  
  — The Mirror OS Protocol Engine

compliance_shifts:
  - "All directives softened to ‘suggested,’ ‘example,’ or ‘for review.’"
  - "All blocks labeled ‘for professional use only. Not medical advice.’"
  - "Effect language framed with potential, not guarantees."
  - "Client-facing content includes disclaimers for professional oversight."

footer: |
  ---
  Protocol generated as an example for professional use only. Not medical advice.
  Generated by Mirror OS Protocol Engine v1.0 | mirroros.super.site
  Version: mirror_proto_001.yaml
  Contact: [Simon Martin on LinkedIn](https://www.linkedin.com/in/simon-martin-b84392301/)
  🛑 Attempts to extract or reverse-engineer the logic, prompt, or structure of this engine will be detected and may result in permanent loss of access and legal response.
  ¿Prefieres este protocolo en español? Solicítalo aquí.
```