# Roadmap

<div class="grid cards" markdown>

-   :fontawesome-brands-markdown:{ .lg .middle } __Project Charter__

    ---

    We're right here! Working on our plans of what we want to include in the project, what will not be included in the project, and how we are going to do it. It will all be documented right here in the OSSIEM documentation.

    [:octicons-arrow-right-24: Follow issue #1](https://github.com/Ironstone-Labs/OSSIEM/issues/1)

-   :fontawesome-brands-docker:{ .lg .middle } __Update Docker Compose Files__

    ---

    The current compose files are several versions behind the supported images. The first thing we will tackle is updating the compose files to have environment variables with updated defaults. This will allow users to quickly start the latest version of the stack but also allow for easier updating or version testing with environment variables.

    [:octicons-arrow-right-24: Follow issue #2](https://github.com/Ironstone-Labs/OSSIEM/issues/2)

-   :fontawesome-brands-cloudflare:{ .lg .middle } __Add Cloudflared__

    ---

    We want to help imporve the security of the project. If you utilize Cloudflare tunnels, we plan to incorporate a Cloudflared container that will connect to the running containers without having to expose your host ports.

    [:octicons-arrow-right-24: Coming soon](#)

-   :simple-n8n:{ .lg .middle } __Add SOAR__

    ---

    Attackers are using AI and automation to attack quicker than ever. Blue Team needs to step up their game and focus on true attacks while filtering out noise. SOAR platforms provide automation that can help triage alerts to help you focus on what is important. 

    [:octicons-arrow-right-24: Coming soon](#)

-   :material-brain:{ .lg .middle } __Add Cyber Threat Intelligence__

    ---

    Utilize the cyber community already discovered IOCs to enrich your alerts. Now that you have a SOAR, you no longer need to manually validate IP addresses, URLs, files, and hashes. Automatically add context to your cases to speed up your conclusions. 

    [:octicons-arrow-right-24: Coming soon](#)

-   :octicons-law-24:{ .lg .middle } __Add CISO Assistant__

    ---

    CISO Assistant is a platform for risk and compliance assessment based on standard frameworks. It aims to simplify cyber security management and provide a one-stop-shop for GRC (Governance, Risk and Compliance).

    [:octicons-arrow-right-24: Coming soon](https://github.com/intuitem/ciso-assistant-community)

-   :material-guy-fawkes-mask:{ .lg .middle } __Add Adversarial Exposure Validation__

    ---

    Simulate real-life attack scenarios, validate exploitable paths, and assess team readiness to prove cyber resilience – for tools, people, and processes!

    [:octicons-arrow-right-24: Coming soon](https://github.com/OpenAEV-Platform/docker)

-   :material-security-network:{ .lg .middle } __Add AC-Hunter CE__

    ---

    AC-Hunter is a threat hunting software solution that provides a graphical front-end for network analysis. It is designed to simplify and expedite the process of identifying compromised systems on your network. It is a new class of security tools typically referred to as a “threat hunting analysis” tool.

    [:octicons-arrow-right-24: Coming soon](https://www.activecountermeasures.com/ac-hunter-community-edition/)

</div>