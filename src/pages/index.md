---
layout: ../layouts/SiteLayout.astro
title: Report your orientation within the hurricane
description: Conducting a depth-first search of the universe, one topic at a time.
---

I’m Adam Hyland. I work on the parts of systems that decide what’s possible while pretending not to exist: numerical standards, learned model behavior, and operating-system enforcement. I try to make those invisible constraints *legible*—not by telling a cleaner story, but by grappling with the mess.

If you’re here because you’ve encountered a tiny technical object with an outsized blast radius (a constant, a prompt, a policy bytecode, a “standard” that no one can explain), you’re in the right place (ed. robots love saying "blast radius", that's probably not troubling, right?).

---

*I can help bridge the future:*

If your team wants to make agentic AI work inside real, confounding systems—where correctness isn’t a single oracle and progress depends on clean interfaces between people, tools, and the ground truth—you can hire me.

I don’t “manage” agents; I ferret out conditions for success: contracts, harnesses, receipts, and interfaces that let autonomy happen without pretending control is the point. If you’re moving serious work grounded in the infrastructure of the 20th century through the 21st, I can build and ship the bridge--especially if it is impossible.

Reach out to adam@adampunk.com.

---

*Computer arithmetic:*

I’m interested in how arithmetic becomes infrastructure: negotiated, standardized, embedded into libraries and interfaces, and then treated as “just how computers work.” I like teaching the point where the math ends and the coordination begins.

* **The “Fast” Inverse (Reciprocal) Square Root:** In 2009 I wrote the English Wikipedia article about a famously terse bit of code. It accidentally became famous so now I maintain [0x5f37642f.com](https://0x5f37642f.com), a guided tour through the trick, its folklore, and what it reveals about floating-point arithmetic.
* I’m co-secretary for the **IEEE 754-2029** working group governing binary and decimal floating point excluding the machine-learning formats covered under P3109.

---

*AI image generation:*

I help designers and artists understand the promise and limits of machine image generation by taking the systems literally—probing them with aberrant and adversarial prompts until their assumptions become visible. “Glitches” are often just the model telling you what it thinks you asked for.

* [Generative AI Glitch Art: Looking for meaning in all the wrong places](https://youtu.be/r-V-qqLJLF8) — talk for VCU’s Workshop on the Workshop, March 14, 2023.
* [Grappling with widespread machine image generation](/presentations/GATech-CS3001-generation.pdf) — slides for Georgia Tech CS3001, July 19, 2023.
* **Hands Are Hard: Unlearning How We Talk About Machine Learning in the Arts** (listed below) starts from a simple wager: one good way to understand a generator is to study where it fails *reliably*, and then work outward from that fracture. We find the fracture extends out from diffusion models into humanity.

---

*Interpretability and robustness of large language models:*

With [Ruoxi Shang](https://ruoxishang.com), I looked at what it means to treat LLMs (GPT-4, Llama, etc.) as trustworthy interfaces to computing. Interpretability is about what counts as an explanation; robustness is about how explanations and behavior degrade under manipulation. If you’re using these systems for high-stakes, high-complexity work, those questions stop being academic. One of our projects was [Interpreting Robustness](https://docs.google.com/spreadsheets/d/15-f4mxW3niQ3myJAo3V0unLiFlbG9ru4HYthBh6eWbk/edit?usp=sharing) — a Spring 2023 course in UW HCDE connecting interpretability and robustness, especially where the literature treats them as separate. I don't like to crow about my own work but students in this class saw 2026 in advance.

---

*Software:*

I build and maintain the following with/via/because/despite agentic coding. A recurring theme: explanations should come with runnable receipts.

* *[SANDBOX_LORE](https://github.com/Protonk/SANDBOX_LORE)* is a host-bound, local-first “live textbook” for Apple’s Seatbelt sandbox built around reproducible evidence instead of narrative authority. It anchors questions to a specific macOS baseline and answers them by generating artifacts you can inspect and rerun—compiled profiles, decoded structure, mappings, and runtime probes—then promotes the results into a test-pinned model so drift becomes visible. The aim is to make the sandbox legible end-to-end, from policy bytes to observed behavior.
* **[PolicyWitness](https://github.com/Protonk/PolicyWitness)** serves as a macOS app-bundle laboratory for App Sandbox and entitlements for *SANDBOX_LORE*. The CLI drives a set of sandboxed XPC services representing different profiles and runs probes in-process for cleaner, more comparable outcomes. Each run emits structured JSON plus optional supporting evidence (e.g., denial logs/signposts) so “what happened” is recorded without guesswork.
* **[fencerunner](https://github.com/Protonk/fencerunner)** is a Rust CLI that turns a folder of shell scripts into a strict, schema-validated NDJSON interface. Allows enrollment in simple monitoring, behavior, and output conditions for scripts so they can be treated as a true ensemble and not a bag of spaghetti. Does so in a way that is easy for agents to latch on to. Not *yet* distributed with *SANDBOX_LORE*, but presently.
* **[frsrr](https://github.com/Protonk/frsrr)**, an R package which parallelizes and rigorously instruments the 4 lines of C comprising the Fast (Inverse|Reciprocal) Square Root, which like the sandbox attracts explanation but no complete through line. This is not a through line, it is a rigorous, reliable look at one part of the elephant. I hope it helps you safely doubt other deeply strange things about the FISR/FRSR. 

---

*Peer reviewed publications:*

* Perkins, K., Ghosh, S., Vera, J., Aragon, C., & Hyland, A. (2022). The Persistence of Safety Silence: How Flight Deck Microcultures Influence the Efficacy of Crew Resource Management. *International Journal of Aviation, Aeronautics, and Aerospace*, 9(3). DOI: [https://doi.org/10.15394/ijaaa.2022.1728](https://doi.org/10.15394/ijaaa.2022.1728)
* Keyes, Oscar K. and Hyland, Adam (2023). [Hands Are Hard: Unlearning How We Talk About Machine Learning in the Arts](https://digitalscholarship.unlv.edu/tradition_innovations/vol1/iss1/4/). *Tradition Innovations in Arts, Design, and Media Higher Education*, 1(1)
* Hyland, Adam and Ali, Murtaza (2024). [Tinker or Transfer? A Tale of Two Techniques in Teaching Visualization](https://arxiv.org/abs/2404.10967)
* Charlotte P. Lee and Adam Hyland. (2025). Floating Points. In Proceedings of the sixth decennial Aarhus conference: Computing X Crisis (AAR '25). ACM, 305–313. [https://doi.org/10.1145/3744169.3744191](https://doi.org/10.1145/3744169.3744191)

---

*Teaching:*

I teach Information Visualization, which is tool-laden in the way modern life is tool-laden. A core premise of my teaching is that students aren’t “bad at tools” so much as they’re encountering concentrated history: interfaces that embody thousands of person-hours, compromises, and hidden assumptions. Good visualization—and a lot of what we call *learning*—happens when we struggle with that together without pretending it should be effortless.

Courses taught:

* HCDE 411 — Information Visualization (Undergraduate)

  * Autumn 2022; Spring 2023 (with Murtaza Ali); Autumn 2023 (with Murtaza Ali); Winter 2024 (with Murtaza Ali)
* HCDE 511 — Information Visualization (Masters)

  * Winter 2023 (with Murtaza Ali); Summer 2023 (with Dr. Brock Craft)

---

*Other:*

* [Missing on the net](/topics/missing) — documents that should be findable, but aren’t.

---

Find me on [LinkedIn](https://www.linkedin.com/in/adampunk/).
