SEER Install — company-scale context layer

id: seer-install
maturity: fruit (Garden) · first packaging file
pass: #5 · 2026-09-11
functions: Content + Profit + Hybrid
public-safe. No client names, no employer names, no prices in this file. Not Seer. Not Consulting. Genesis retired.

Before

LOCKS names the method: "Company-scale install; Genesis retired." GARDEN lists it as fruit. ideas/seer-personal-os.md draws one boundary: "Install a markdown/context layer, train, leave. Seer never leaves the owner; Install must."

What was missing: a file a stranger can read and answer three questions from. What do I get? What do you take away when you leave? What is mine on day 30? Nothing on Rsee answered them. Fruit with no packaging is a name, not an offer.

Offer

One sentence. SEER Install puts a plain-text context layer inside a company, trains the people who will own it, and leaves.

What it is. A set of Markdown files, in a git repository the client owns, that make the client's own definitions, rules, decisions, and sources loadable by any AI model the client chooses. The model is staff on demand. The files are the algorithm. The client holds both.

What it is not.

Not a chatbot, and not a retainer to keep a chatbot fed. The deliverable is the layer, not a seat.
Not a dashboard shop. Interfaces are generated from the layer on request and thrown away. The layer is kept.
Not a model choice. The layer is vendor-independent by construction and is loaded into two different models before we leave.
Not "transformation." Fixed scope, dated start, dated exit. The open-ended framing (Genesis) is retired.
Who it is for. An organization with one accountable owner for the layer, knowledge that lives in a few heads, and at least one recurring number that has to be right. If nobody will own the writer's seat, we do not install.

How it is priced. Per install, fixed, with the exit date in the agreement. Nothing monthly for the layer to keep existing. Numbers are not public and are still open below.

Install · Train · Leave

Default shape: thirty days. Week one installs the files. Weeks two through four train the people. Day thirty we leave. Move the calendar if you must; never the order.

Install (days 1–7) — the files exist

Deliverable	File in the client's repo	What it answers
Constitution	CONSTITUTION.md	What counts as canon here, what evidence promotes a fact, when the model must stop and ask. Written in the owner's own words from a recorded interview.
Standing rules	RULES.md	Loaded every session: accuracy over speed, facts and assumptions labeled apart, propose before write, date every fact, regulated data never leaves its system of record.
Knowledge base, tiered	canon/gold/ · canon/silver/ · canon/bronze/	Gold is settled canon, always loaded. Silver is confirmed facts with a source and a date. Bronze is raw capture, searched, never loaded. Promotion needs evidence.
Envelopes	envelopes/<task>.md	One profile per task type (auditing a query, reconciling two numbers, writing for leadership) with its gates and its stop-and-escalate line. Three at install. The client adds more only on real need.
Source map	SOURCE_MAP.md	Which system holds the true number for each family of questions, at what grain, how fresh, who has access.
Decision log	DECISIONS.md	Dated entries with source and confidence. Supersede; never silent-rewrite.
Idea capture	PENSIEVE.md	One-line capture, weekly refinement pass.
Validator and build	tools/validate · tools/build · CI	Checks front matter, ids, and a denylist of names and secrets; generates the entry file. Plain scripts with no dependencies, readable by the client's own people.
Entry file	DOOR.md (generated)	The smallest true file a model loads first. Never hand-edited.
First live reconciliation	reconciliations/0001.md	Two numbers that must match, tolerance declared before looking, evidence recorded. The install pays for itself the first time it catches a drift.
Train (days 8–28) — the people can run it

Harvest. Twenty-minute sessions with the people who hold the knowledge, using a four-part instrument: constitution, facts only you know, operational calls, open mic. Each answer lands in silver with a source and a date. Deliverable: training/HARVEST_GUIDE.md and the silver files themselves.
Owner. How to read a proposal, run the validator, merge, and revert. Deliverable: training/OWNER.md.
Writer. One named writer. Everyone else, models included, proposes. Deliverable: the propose-before-write rule in RULES.md and a pull-request template.
Weekly pass. Thirty minutes, a calendar entry, run three times with us in the room before we leave. Deliverable: training/WEEKLY_PASS.md.
Two-model test. The same DOOR.md loaded into two different vendors' models, the same fixed question set, answers within the declared tolerance. Result recorded in DECISIONS.md.
Session logs. Every session that changes files leaves a log in sessions/. The logs are the client's, not ours.
Leave (day 30) — the Legacy Test

The test. Someone who was in none of the sessions loads DOOR.md and one envelope, answers a real question, and cites the governing rule by file. Pass means we leave. Fail means the exit date moves and the reason is written in DECISIONS.md.
Revoke. Our access to the repository and to any client system is removed by the client and recorded.
Handoff. HANDOFF.md: what exists, what is open, who owns what.
Delete. Our working notes that contain client facts are deleted by day 30, not archived.
What the client owns on day 30

Everything in the repository, in plain text, under the client's own account: constitution, rules, all three tiers, envelopes, source map, decision log, idea capture, tools, CI, the entry file, the training guides, the reconciliation records, the session logs. A trained owner and a named writer. A weekly ritual on the calendar.

The right to load the layer into any model, including an open-weights model on the client's own hardware. No hosted service, no license key, no proprietary format, no dependency on us. If we disappear on day 31, nothing stops working.

What leaves with us: the method. The shape of the files, the gates, the discipline, with zero client facts. A pattern crosses only if it is publishable as it stands, describes a mechanism and not a value, would help a stranger in another industry, and is sourced to experience and a date rather than to a named engagement. Each crossing gets one dated line in our own log, so the claim can be checked later.

What we take away: our access, our accounts, and nothing else.

What we refuse

Regulated or personal data leaving the client's system of record. De-identification happens inside it, before anything moves. A task that needs the raw data stops.
A retainer to "keep the AI fed." If the layer needs us every month, the install failed.
Hosting the client's canon on our infrastructure or inside our vendor account.
A layer that works with only one model or one tool.
A companion persona. The model is an instrument on the client's desk. Anti-Attachment applies inside companies too.
Installs with no named owner and no named writer. Knowledge replicates everywhere; authority lives in one place, and that place is a person.
Client names, employer names, or system names in anything we publish, this file included.
Open-ended engagements. No exit date, no install.
Maintaining dashboards. Interfaces are disposable; the layer is not.
Promising accuracy without gates. A confident wrong number costs more than a slow right one.
Hybrid — boundaries

Neighbor	Boundary
Seer (personal OS)	Same organs, constitution, tiers, envelopes, decision log, idea capture, with a different owner. Seer never leaves the owner; Install must leave the client. Nothing from a client enters Seer except a mechanism that passes the crossing test above.
SEER Consulting	Consulting is human counsel with analytics inside the work, retained by the hour or the question. Install is a dated engagement with an exit. Consulting may follow an install. It may never be the install wearing a longer contract.
Open-LLM orientation	Honored as a test, not a slogan. Before Leave, DOOR.md must load into at least one open-weights model, and the layer carries no vendor-specific prompt format. The client may stay with a closed vendor; the client is never forced to.
GRAIN (five grains)	GRAIN owns the vocabulary of record types. Install adopts the client's grains or GRAIN's, and never mints a sixth.
Anti-Attachment	Bouncer at install too. A client who asks the model to "remember people" gets a decision log, not a memory of persons.
Idea Garden and Seer Chronicle	Install is fruit in the Garden and may stamp a beat in the Chronicle. It publishes no client content to either.
The hybrid claim: an install has worked only if the installer has become unnecessary. Anything that keeps us necessary is a defect in the install.

Still open (≤3)

Pricing shape. Per install, fixed, dated exit is the stance. Numbers stay private until Settled.
The Legacy Test as a written checklist, training/LEGACY_TEST.md. Settled only after one real run.
First client shape. Sequence not decided here.
After

ideas/seer-install.md exists on main. A stranger can answer the three questions. Pages not rewritten. Private see-r-os not invented.
