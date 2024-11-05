---
layout: post
title: "Architect's Perspective on AEC TECH 2024"
author: "Laszlo Andrasi"
categories: Posts
tags: [posts]
image: AEC-Tech-2024.jpg
---

# AEC TECH 2024

I was fortunate to attend my first AEC Tech Symposium this year. The AEC Tech is an annual event focused on technology advancements in the Architecture, Engineering, and Construction (AEC) industries. Organized by the nonprofit **Thornton Tomasetti CORE studio**, it brings together professionals, technologists, and academics interested in digital innovation within AEC. The symposium includes workshops, presentations, and networking opportunities centered on computational design, building information modeling (BIM), digital fabrication, artificial intelligence, and other cutting-edge technologies in the field. 

The week long event is composed of both virtual and in-person workshops, tech crawls and tours, a symposium, and ending on a 26 hour hackathon over the weekend. The event is designed to encourage knowledge exchange, showcase emerging tools and workflows, and foster collaboration among industry experts and technology enthusiasts. Each year’s symposium has a different theme that highlights current trends and challenges, offering both practical and theoretical insights on the evolving role of technology in AEC.

Thank you again to the Bill Berger and the Chicago Studio, as well as Nick Cameron and the entire Digital Practice team for the opportunity to attend AEC Tech this year. I learned a lot and am looking forward to bringing back some of the innovative tools and energy back to Perkins&Will.

[<img src="https://laz-ap.github.io/thoughts/assets/img/AEC Tech - Event Image.png" style="width:100%; max-width:1024px; height:auto;">>](https://www.aectech.us/)

# Workshops

<img src="https://laz-ap.github.io/thoughts/assets/img/In person workshop.png" style="width:100%; max-width:1024px; height:auto;">

I started off the AEC Tech experience with an all day workshop with CORE Studio called, Transforming Text: Practical NLP for the AEC Industry. Funny enough was the fact that half of the Perkins&Will attendees, 7 total, also had the same idea. 

The session was hosted by **Seyedomid (Omid) Sajedi**, Senior AI & ML Engineer at Core Studio. The **CORE studio's Transforming Text: Practical NLP for the AEC Industry** workshop is a hands-on, half-day session designed for AEC professionals looking to streamline document review processes using natural language processing (NLP) tools. Given the time-intensive nature of document analysis in AEC, this workshop introduces practical NLP techniques to improve productivity and automate text-heavy tasks.

[![LinkedIn Profile Image](https://laz-ap.github.io/thoughts/assets/img/Omid+Sajedi.jpg)](https://www.linkedin.com/in/seyedomid-sajedi-263b703a/)


The workshop started with setting up a Python environment on either a local machine or Google Colab. We then started with an initial exercise learning basic NLP techniques, starting with [spaCy](https://spacy.io/). This NLP library excels in tasks like tokenization, part-of-speech tagging, and named entity recognition. The first part covered various machine learning and non-machine-learning techniques for automating document processing, giving us practical tools that could simplify some of the more text-heavy tasks in our work.

### Confusion Matrix from first excercise 

<img src="https://laz-ap.github.io/thoughts/assets/img/Confusion Matrix.png" style="width:100%; max-width:1024px; height:auto;">

In the Deep Learning and Transformers section, we explored advanced NLP concepts, beginning with the fundamentals like tokenization and text embeddings. We also learned how to use unsupervised learning methods—such as topic modeling with small language models—to uncover insights from large document collections. One highlight was building an AI-powered semantic search tool using Retrieval Augmented Generation (RAG), and we even experimented with NLP agents to boost the reasoning abilities of language models. The workshop was beginner-friendly but required some basics, like a laptop, internet connection, and Google account for exercises on Jupyter Notebooks via Google Colab. For the final exercise, we needed minimal paid API access. 

### [Multi-Agent](https://microsoft.github.io/autogen/0.2/docs/Use-Cases/agent_chat/)

<img src="https://laz-ap.github.io/thoughts/assets/img/multi-agent-workflow.png" style="width:100%; max-width:1024px; height:auto;">


# Symposium

<img src="https://laz-ap.github.io/thoughts/assets/img/Symposium.png" style="width:100%; max-width:1024px; height:auto;">

The workshop on Thursday was all about learning information about a specific skill, Natural Language Models, an intense academic heavy day. Friday on the other hand was equally as intense but focused entirely on listening to presentations, keynote speeches and panel discussions. The Theme of this year's Symposium was reflecting on the state of practice today and what is on the horizon.

<img src="https://laz-ap.github.io/thoughts/assets/img/Panel 1.jpg" style="width:100%; max-width:1024px; height:auto;">

Beginning at 9:00 am, the event commenced with a welcome and introductory remarks, setting the stage for a packed agenda. Shortly afterward, presentations began with [**Nicholas Desbiens**](https://www.linkedin.com/in/nicholasdesbiens/) and [**Amir Ashtiani**](https://www.linkedin.com/in/amir-ashtiani-7b705b33/) from [**Pininfarina**](https://pininfarina.it/), who shared their insights into innovation in design and computational techniques. Nicholas discussed how Pininfarina integrates technology into various design fields, while Amir focused on how AI-driven visualization is reshaping architectural practice, challenging traditional methods, and exploring new possibilities.

The morning continued with a presentation by [**Justin Hattendorf**](https://www.linkedin.com/in/jhattendorf/) from [**nTop**](https://www.ntop.com/), who introduced us to their computational design platform aimed at high-performance engineering. Justin emphasized the importance of user-friendly interfaces for complex workflows, drawing on his background in 3D modeling and industrial design. This presentation inspired my later hackathon idea of having real time analysis be integrated while modeling, giving designers real time data on their projects.

Following Justin, [**Michael Szivos**](https://www.linkedin.com/in/michael-szivos-bbb39322/) from [**SOFTlab**](https://soft-lab.com/) showcased his studio's unique approach, which merges technology, craft, and material experimentation to blur the lines between architecture, art, and interactive design. Showing how the studio has evolved to incorporate technology with beautiful public works such as [Ventricle](https://soft-lab.com/project/ventricle/) and the [nautilus](https://soft-lab.com/project/nautilus/). 

The keynote address by [**Shajay Bhooshan**](https://www.linkedin.com/in/shajaybhooshan/) from [**Zaha Hadid Architects**](https://www.zaha-hadid.com/) was a capped off the morning, where Shajay detailed how ZHA’s CODE group applies computational design to create advanced architectural forms, particularly shell structures. A large part of the keynote presentation was showing how architectural knowledge provide unique opportunities in the VR and gaming space. Their studio has been working with Epic Games and the Fortnite team to make interactive and educational architecture spaces. They define a kit of parts the gamers use to impact the urban fabric of existing cities.

<img src="https://laz-ap.github.io/thoughts/assets/img/Panel 2.jpg" style="width:100%; max-width:1024px; height:auto;">

After the first series of presentations and a short panel discussion, the next item on the agenda was a roundtable discussion moderated by [**Perkins&Will**](https://perkinswill.com/) Associate Digitial Innovation Strategist [**Charles Portelli**](https://www.linkedin.com/in/charlieportelli/), consisting of emerging technologists in the AEC space. The line up included; [**Dimitrie Stefanescu**](https://www.linkedin.com/in/dimitrie/) / Founder & CEO @ [**Speckle**](https://speckle.systems/); **Wouter Riedijk** / CSO & Co-Founder @ [**Viktor**]([https://speckle.systems/)](https://www.viktor.ai/); [**Andrew Heumann**](https://www.linkedin.com/in/andrew-heumann-13751414/) / Software Developer @ [**Hypar**](https://hypar.io/); [**Mathias Hobinger**](https://www.linkedin.com/in/mathiashoebinger/) / Co-founder & CEO @ [**Shapediver**](https://www.shapediver.com/). The discussion included questions on how they ended up in the AEC software development space, whether or not their products will be open source, and where they expect the industry to be heading. Probably my favorite quote of the symposium was from Dimitrie, the panel was asked whether or not automation should be pursued by firms, even when they can be potentially fragile and tempermental. Dimitrie responded along the lines of there are two types of automation, ones that focus on the micro tasks and those that focus on the macro. Automating micro tasks allow for people to be freed up from tedious activies that distract us from what humans excel at, critical thinking and navigating complex problems. These micro automations also tend to be more robust and flexible, allowing for less up keep. This resonated with me as an *architect* because there has been an emphasis in the artifical intellegence discource around automating visualization, layouts, and even architectural design, all things I know my fellow architects enjoy and are experts in. If AEC firms focus on freeing up our human capital from micro tasks, such as filling out time sheets, filing RFIs, or running basic analysis, then our teams can focus more time on developing innovative solutions.

<img src="https://laz-ap.github.io/thoughts/assets/img/Panel 3.jpg" style="width:100%; max-width:1024px; height:auto;">

After a lunch break, the afternoon resumed with presentations from [**Alexandra Pollock**](https://www.linkedin.com/in/alexandrapollock/) / Senior Director of [**TT CORE Studio**](https://www.thorntontomasetti.com/core-studio), [**Petr Mitev**](https://www.linkedin.com/in/petr-mitev/) / Vice President, Solutions for Designers @ [**Chaos**](https://www.chaos.com/), [**Dan Reynolds**](https://www.linkedin.com/in/dan-reynolds-16b7b21b/) / AI Leader @ [**Walter P. Moore**](https://www.walterpmoore.com/), and [**Andrew Kragness**](https://www.linkedin.com/in/akragness/) / Director of Computational Design @ [**Martin Bros. Construction**](https://www.martinbros.net/). Alexandra shared her extensive experience in AEC technologies, describing CORE Studio’s initiatives in both super-tall towers and digital innovation, while Petr discussed his work in leveraging software to improve design and delivery processes. Both talks provided compelling perspectives on how technology is enhancing efficiency and creativity in the AEC industry. Afterwards Dan spoke about how AI is being used in his firm to build custom solutions and give his engineers tools to help them design rather then design for them. Lastly, Andrew with Martin Bros showcased how computational design can be used by Contractors as well, creating improved solutions in the design build work they are doing on the [Lucas Museum](https://lucasmuseum.org/) in Los Angeles. 

<img src="https://laz-ap.github.io/thoughts/assets/img/Panel 4.jpg" style="width:100%; max-width:1024px; height:auto;">

The day concluded with a lively roundtable titled "Grasshopper Plugin Pioneers," moderated by **Brian Gillespie** Product Manager @ [**Robert McNeel and Associates**](https://www.rhino3d.com/). This session featured industry leaders like [**Mostapha Sadeghipour Roudsari**](https://www.linkedin.com/in/mostapha-roudsari/) / Co-Founder of [**Ladybug Tools**](https://www.ladybug.tools/), [**Nathan Miller**](https://www.linkedin.com/in/nmillerarch/) / CEO @ [**Proving Ground**](https://provingground.io/), **David Mans** / VP Applications Developer @ [**TT CORE Studio**](https://www.thorntontomasetti.com/core-studio), and [**Andrew Heumann**](https://www.linkedin.com/in/andrew-heumann-13751414/) / Software Developer @ [**Hypar**](https://hypar.io/) who shared the development journeys and applications of their popular Grasshopper plugins. They highlighted how these tools empower designers with sophisticated workflows for geometry, data, and automation. Finally, the event wrapped up with closing statements from Robert Otani, CTO of Thornton Tomasetti, emphasizing the future potential of technology in transforming architectural and engineering practices. [**Robert Otani**](https://www.linkedin.com/in/robert-otani-pe/) / CTO @ [**TT CORE Studio**](https://www.thorntontomasetti.com/core-studio) provided the closing statement for Friday's Symposium, speaking to the exciting developments in the AEC showcased that day. Overall I was left with the impression that our industry is on the edge of a coming explosion in accessible tools for interoperability, innovation, and automation.

# Hackathon

<img src="https://laz-ap.github.io/thoughts/assets/img/hackathon.png" style="width:100%; max-width:1024px; height:auto;">

I will most likely end up posting a dedicated blog post on the details of my proposed hack, Splash, and will instead speak about the unique experience around the Hackathon itself. Kicking off Saturday's Hackathon with a short presentation at 9:30am, the Hackathon was scheduled for a 26 hour sprint, with all submissions due by 11am the following day. A unique part of Hackathon's are the Lightning Rounds pitches at the beginning of event where anyone can stand in front of the attendees and pitch an idea for a hack. Perkins&Will had a strong contigent of 15 hackers for the event, and 4 of us decided to brave the Lightning Round and pitch our own ideas. [**Anish Reddy**](https://www.linkedin.com/in/anish-reddy-28167b16/) pitched an idea on *AI copilot for grasshopper* and *Quantify added value to projects based on localized data*, I pitched an idea on *automating analysis using Speckle Automate and Rhino.Compute*, [**Anthony Samaha**](https://www.linkedin.com/in/anthony-samaha/) pitched *Image Markers as an alternative to QR codes fees,* [**Kart Gopinath**](https://www.linkedin.com/in/kartt-gopinath/) pitching developing tools for *optimizing Revit warnings mitigation*, lastly **Luke Gehron** pitched *D-AI-LOG, using AI Prompts to create geometry*. We all ended up working with full teams consisting of total strangers. 

<img src="https://laz-ap.github.io/thoughts/assets/img/Hackathon Pano.jpg" style="width:100%; max-width:1024px; height:auto;">

Hackathons provide a unique opportunity to join a team of complete strangers and dive into a problem. This being my first hackathon experience, I was impressed with how quickly teams reached a flow state and solved complex problems. I look forward to applying this learning experience in future collaborative efforts.

### Click on the Splash Logo for the GitHub!
[<img src="https://laz-ap.github.io/thoughts/assets/img/Splash!.png" style="width:100%; max-width:1024px; height:auto;">](https://github.com/team-speckle-automation)

# Closing Thoughts

In closing, AEC Tech 2024 was a truly inspiring and transformative experience. The depth of knowledge, innovative ideas, and cutting-edge technologies showcased throughout the event highlighted the exciting trajectory of our industry. From the workshops and symposium to the hackathon, each segment offered fresh insights into how digital tools are reshaping architecture, engineering, and construction. The event underscored a crucial shift toward collaboration and interdisciplinary learning—paving the way for greater integration of technology and automation in AEC.

A big thank you to Thornton Tomasetti CORE Studio and the dedicated professionals who made this event possible. I leave AEC Tech 2024 energized and full of ideas, eager to bring these new tools, workflows, and perspectives back to Perkins&Will. Here’s to a future where technology continues to empower designers, enhance efficiency, and unlock new possibilities in our field.

<img src="https://laz-ap.github.io/thoughts/assets/img/PW_AEC Symposium.jpg" style="width:100%; max-width:1024px; height:auto;">
