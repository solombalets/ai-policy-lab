## 🧠 Problem

Pro-regime Russian Telegram channels play a key role in the information and psychological war—not only against external enemies, but also against exiled regime critics. These channels promote a narrative in which loyalty to the Kremlin becomes the main criterion of Russian identity, while dissenters are labeled "trans-Ukrainians," "transnationals," or simply "traitors." At the same time, the authors often adopt a pseudo-oppositional, anti-establishment tone, borrowing stylistic cues from Western populism, despite being deeply embedded in the Russian state apparatus. This creates a form of "official nationalism" dressed in rebellious aesthetics.

Such channels display striking ideological ambiguity: on the one hand, they claim to represent an authentic “Russian voice,” yet they eagerly include Chechens, Tatars, and other non-Russian actors as “true Russians” as long as they support the empire’s agenda. National identity is redefined not through ethnicity, culture, or civic values, but through political loyalty. Alternative conceptions—such as ethnocultural nationalism, the idea of a Russian nation-state, or even decolonial critique—are ridiculed or smeared. The resulting discursive noise serves a gaslighting function: it disorients, undermines coherent identity frameworks, and prevents the formation of a stable oppositional narrative.

## 📦 Data

A corpus of posts from 5–10 popular pro-Kremlin Telegram channels (e.g., “Major & General,” “Rybar,” “Rosich,” “Readovka,” “Voenny Osvedomitel”).

Collected content: posts from the past six months, filtered for references to exiled Russians, "trans-Ukrainians," RDK, Chechen fighters, Western critics, concepts of "Russianness," "national traitors," and decolonization.

Data collection methods: `telethon` or `snscrape` via Telegram API, or pre-built Telegram datasets (e.g., on HuggingFace or GitHub).

## 🛠️ Method

- **Topic modeling** (BERTopic or LDA): to extract key themes and discourse clusters.
- **NER / keyword spotting / regex**: to track specific ideological markers (e.g., “trans-Ukrainian,” “Russian,” “traitor,” “Chechnya,” “West,” “colonialism”).
- **LLM-assisted contradiction detection**: using OpenAI API to highlight rhetorical contradictions, conceptual shifts, and narrative doublespeak.
- **Temporal analysis**: tracing how themes evolve over time in response to news events (e.g., RDK incursions).
- **Visualization (matplotlib, Plotly, Altair, pyvis)**: to show clusters, narrative overlaps, and ideological contradictions in intuitive formats.

## 🎯 Expected Outcomes

- **Discourse cluster map**: visualizing key narratives and how they interact or contradict one another.
- **Examples of rhetorical contradictions**: showcasing how these channels gaslight their audiences and obscure ideological positions.
- **Temporal evolution**: a timeline showing shifts in messaging in reaction to real-world events.
- **Narrative analysis**: unpacking how regime-friendly actors redefine “Russianness,” delegitimize dissidents, and claim monopoly on identity through propaganda.

