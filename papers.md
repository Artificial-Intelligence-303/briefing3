# Briefing 3: themes and papers

Six themes, one group on each. Your group picks a theme in class and reads the paper listed under it.
Every paper describes an AI system that is in use, was presented at **IAAI-26**, and was published on
**March 14, 2026**. All of them are free to read.

---

## 1. Food rescue in Pittsburgh

An AI reads what volunteers write after each food pickup and tells organizers which donors and
recipients to contact.

- **RescueLens: LLM-Powered Triage and Action on Volunteer Feedback for Food Rescue.** Naveen Janaki
  Raman, Jingwu Tang, Zhiyu Chen, Zheyuan Ryan Shi, Sean Hudson, Ameesh Kapoor, Fei Fang. Proceedings
  of AAAI-26.
  https://doi.org/10.1609/aaai.v40i47.41444

  **How to read it:** Read sections 1, 3, 6 and 7. In section 5, read the first paragraph and Table 1;
  precision is the term from class, and recall is the true positive rate.

## 2. Watching the numbers in public health

An AI ranks up to 5 million public health data points a day so that a small team of reviewers knows
where to look first.

- **Reducing Alert Fatigue Through AI Ranking: A Deployed Public Health Data Monitoring System.** Ananya
  Joshi, Nolan Gormley, Richa Gadgil, Catalina Vajiac, Tina Townes, Roni Rosenfeld, Bryan Wilder.
  Proceedings of AAAI-26.
  https://doi.org/10.1609/aaai.v40i47.41435

  **How to read it:** Read it all; it is written around the people who review the data. Skim the
  descriptions of the three interaction modes, M1 to M3.

## 3. A search engine for trafficking investigations

More than 200 US law enforcement agencies searched over 100 million online ads with an AI system that
links phone numbers, emails and locations. The paper describes sex trafficking investigations and
court cases.

- **A Deployed Investigative AI Search Engine for Combating Human Trafficking at Web Scale.** Mayank
  Kejriwal. Proceedings of AAAI-26.
  https://doi.org/10.1609/aaai.v40i47.41436

  **How to read it:** Read the introduction, "Deployment and Real-World Use" and "Lessons Learned". Skim
  "Knowledge Graph (KG) Construction and Representation" and "Query Reformulation and Search". In "Experimental Validation",
  NDCG is a score for how high the right results are ranked: higher is better.

## 4. An AI that drafts a judge's reasoning

A state court in Brazil uses language models to draft the reasoning behind judges' decisions.

- **SARA: Leveraging LLM Agents and Jurisprudential Ontologies for Automated Legal Reasoning.** Francisco
  C. J. Bonfim, Sara Pessoa Silva, Alicia S. Neves, Henrique Santos, João A. Monteiro Neto, Jorge L. B.
  Araujo, Rilder S. Pires, Ricardo Alexandre Da Silva Costa, Vasco Furtado, Vladia Pinheiro. Proceedings
  of AAAI-26.
  https://doi.org/10.1609/aaai.v40i47.41425

  **How to read it:** Read the abstract, the introduction and the conclusion, where the judges' feedback
  and the number of users are. Skip the ontology and the Turtle code in the SARA section. The
  evaluation's AlignScore and BERTScore measure how close the AI's wording is to the judges' own; you do
  not need to know how they are computed.

## 5. Cameras on construction workers

Helmet cameras, site cameras and drones feed an AI that flags safety violations and sends each worker a
correction.

- **ConstructAI: From Real-Time Safety Insight to Skill Growth in Deployed Construction AI Systems.**
  Gaowei Zhang, Wei Wang, Tiong Lee Kong, Kai Xing, Huan Li, Yi Wang. Proceedings of AAAI-26.
  https://doi.org/10.1609/aaai.v40i47.41452

  **How to read it:** Read the introduction, "Our Approach in a Nutshell", the case studies, Table 1 and
  "Lessons Learned". Skip "Training and Testing", Table 2 and the loss formula: they are about training
  the model, not about what happened on the sites.

## 6. Rating hurricane damage from drone photos

After two hurricanes in Florida, an AI rated the damage to 415 buildings from drone photographs for
emergency managers.

- **Deploying Rapid Damage Assessments from sUAS Imagery for Disaster Response.** Thomas Manzini,
  Priyankari Perali, Robin R. Murphy. Proceedings of AAAI-26.
  https://doi.org/10.1609/aaai.v40i47.41474

  **How to read it:** Read the introduction, "Operator Training" and "Deployment at Hurricanes Debby &
  Helene". In "Model Development", skip the model names; F1 is a score from 0 to 1 for how well damage
  was rated, and the random baseline is 0.175.
