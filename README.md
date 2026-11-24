# Common Ground

A collection of thirteen classroom games about collective action, climate cooperation and Nash equilibrium. Each game explains its rules, research context and selected bot strategies.

## Play

[Choose a game](https://aletavoni.github.io/common-ground/games.html), or open one directly:

| Game | Play online | Focus |
| --- | --- | --- |
| Common Ground: The private solution trap | [Play](https://aletavoni.github.io/common-ground/) | Private protection versus a shared public solution; four players. |
| Climate Coordination | [Play](https://aletavoni.github.io/common-ground/climate-coordination.html) | Inequality, nonbinding pledges and a shared climate target; six players. |
| Climate Clubs | [Play](https://aletavoni.github.io/common-ground/climate-clubs.html) | Treaties, conditional commitments, sanctions and retaliation; three nations. |
| IF/THEN: The commitment game | [Play](https://aletavoni.github.io/common-ground/if-then.html) | Conditional cooperation and the most cooperative compatible outcome; 2–15 players. |
| Last Call | [Play](https://aletavoni.github.io/common-ground/last-call.html) | Bargaining, unequal endowments, binding side deals and shrinking targets; six countries. |
| Civic Desk | [Play](https://aletavoni.github.io/common-ground/civic-desk.html) | Representation, nonbinding advice and costly punishment; four teams. |
| The Dial | [Play](https://aletavoni.github.io/common-ground/the-dial.html) | Public Good-or-Bad provision, free-riding and free-driving; three players. |
| Mandate | [Play](https://aletavoni.github.io/common-ground/mandate.html) | Strategic delegation with linear or quadratic benefits; principal and agent seats. |
| Switchboard | [Play](https://aletavoni.github.io/common-ground/switchboard.html) | Conventions, social tipping, pair versus group coordination and multiple Nash equilibria; 8 or 16 players. |
| Watershed | [Play](https://aletavoni.github.io/common-ground/watershed.html) | 4 players; 3 networks. |
| Catalyst | [Play](https://aletavoni.github.io/common-ground/catalyst.html) | 7 players; 6 treatments. |
| Quorum | [Play](https://aletavoni.github.io/common-ground/quorum.html) | 4 teams; 6 cases. |
| Fogline | [Play](https://aletavoni.github.io/common-ground/fogline.html) | 6 players; 10 rounds. |

Each game is a self-contained HTML file and runs entirely in your browser, with no installation, sign-in or server-side code. Bots follow the benchmark explained in each guide, including selected Nash strategies and a robust maximin benchmark for Fogline’s ambiguity treatment. They are not estimates of research participants' behavior. Teaching adaptations and equilibrium assumptions are described in each app's guide.

Choices remain in browser memory and reset on refresh. CSV exports are generated locally. The apps have no analytics or external runtime dependencies; the hosting provider may keep ordinary access logs.

### Private solution trap: unknown bot plans

Alongside the two disclosed bot plans, choose **What will the others do?**. Each bot gets its own independent 50/50 draw every round, so Ada can draw private while Sam draws public in the same round. On a private draw, each bot invests up to 20 units toward its own 60-unit protection target, and stops once it reaches that target. On a public draw, each bot invests up to 4 units publicly. In both cases a bot cannot invest more than its remaining budget.

Each bot’s plan and contribution are revealed immediately after you confirm your choice. The round history shows each bot’s past draws and contributions, plus the cumulative public total. Past draws don’t affect the next ones. Results summarize the draws and compare your payoff with the best possible payoff had you known the bots’ realized public total from the start.

CSV exports retain the selected setup in `mode` (`private`, `public` or `unknown`) and record each bot’s plan for that round in `bot_mode` (`private` or `public`). That field is blank for the human player.

## Research

* **Private solution trap:** Malthouse et al. (2026), *The private solution trap in collective action problems across 34 nations*, PNAS 123, e2504632123. [Paper](https://doi.org/10.1073/pnas.2504632123).
* **Climate Coordination:** Tavoni, Dannenberg, Kallis and Löschel (2011), *Inequality, communication, and the avoidance of disastrous climate change in a public goods game*, PNAS 108, 11825–11829. [Paper](https://doi.org/10.1073/pnas.1102493108).
* **Climate Clubs:** Casari and Tavoni (2024), *Climate clubs in the laboratory*, Journal of Behavioral and Experimental Economics 110, 102211. [Paper](https://doi.org/10.1016/j.socec.2024.102211).
* **IF/THEN:** Casari, Ordaz-Cuevas and Tavoni, *“I Will If You Will” in Climate Mitigation: Conditional Cooperation in the Lab*, working paper supplied by the author.
* **Last Call:** Gosnell and Tavoni (2017), *A bargaining experiment on heterogeneity and side deals in climate negotiations*, Climatic Change 142, 575–586. [Paper](https://doi.org/10.1007/s10584-017-1975-3).
* **Civic Desk:** Kim, İriş, Lee and Tavoni (2025), *Representation, Peer Pressure and Punishment in a Public Goods Game*, Environmental and Resource Economics 88, 1407–1433. [Paper](https://doi.org/10.1007/s10640-025-00970-6).
* **The Dial:** Heyen, Lohse and Tavoni, *Public Gobs in the Lab*, supplied working paper dated 13 November 2026.
* **Mandate:** Schmid, Tavoni and Winkler, *Strategic Delegation in a Standard Public Goods Game*, supplied October 2026 working paper.

* **Switchboard:** Wieczorek, Pizziol and Tavoni, *Social Tipping Points: An Experiment*, working paper supplied by the author on 16 November 2026. Implements all four G8/P8/G16/P16 treatments, selected pure and symmetric mixed Nash bots, 5+5 or 21+21 periods, and a separate two-option tipping calculator. The 420/600 payoff equation is preserved; bot selection and classroom adaptations are explained in the app.

* **Watershed:** Shreedhar, Tavoni and Marchiori (2020), *Monitoring and punishment networks in an experimental common pool resource dilemma*, Environment and Development Economics 25, 66–94. [Paper](https://doi.org/10.1017/S1355770X19000457).
* **Catalyst:** Bosetti, Heugues and Tavoni (2017), *Luring others into climate action: coalition formation games with threshold and spillover effects*, Oxford Economic Papers 69(2), 410–431.
* **Quorum:** İriş, Lee and Tavoni (2019), *Delegation and Public Pressure in a Threshold Public Goods Game*, Environmental and Resource Economics 74, 1331–1353. [Paper](https://doi.org/10.1007/s10640-019-00371-6). Its guide explains the integer-grid Nash verification and the differences from parts of the paper’s rounded benchmark table. This is a different paper from Mandate.
* **Fogline:** Dannenberg, Löschel, Paolacci, Reif and Tavoni (2015), *On the Provision of Public Goods with Probabilistic and Ambiguous Thresholds*, Environmental and Resource Economics 61, 365–383. [Paper](https://doi.org/10.1007/s10640-014-9796-6).

## Publish with GitHub Pages

In the repository's Settings → Pages, select **Deploy from a branch**, then **main** and **/ (root)**. Save and wait for the deployment to finish. Use the live URL shown on that page to share the game.

Only generated teaching apps and this menu are included here. Research PDFs, participant data and other local workspace files are not part of the website.
