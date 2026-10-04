# ENGLISH GRAMMAR — CHEATSHEET FOR SOFTWARE ENGINEERS

### VERB-FORM KEY

| V1 (Base) | V2 (Past) | V3 (Past Participle) | V4 (-ing) | V5 (s/es) |
| --- | --- | --- | --- | --- |
| **go** | **went** | **gone** | **going** | **goes** |
| **build** | **built** | **built** | **building** | **builds** |
| **write** | **wrote** | **written** | **writing** | **writes** |
| **run** | **ran** | **run** | **running** | **runs** |
| **break** | **broke** | **broken** | **breaking** | **breaks** |
| **fetch** | **fetched** | **fetched** | **fetching** | **fetches** |
| **catch** | **caught** | **caught** | **catching** | **catches** |
| **set** | **set** | **set** | **setting** | **sets** |
| **deploy** | **deployed** | **deployed** | **deploying** | **deploys** |
| **commit** | **committed** | **committed** | **committing** | **commits** |
| **merge** | **merged** | **merged** | **merging** | **merges** |
| **rollback** | **rolled back** | **rolled back** | **rolling back**| **rolls back** |
| **override** | **overrode** | **overridden** | **overriding** | **overrides** |

---

### TENSES

#### Core Rules

* **I / You / We / They** → **V1**
* **He / She / It** → **V5** in Present Simple
* After **did** → always **V1** (*Did you check the logs?*)
* After **does** → always **V1** (*Does this API support authentication?*)
* After **do** → always **V1** (*Do you need any help?*)
* After **has / have / had** → **V3**
* After **am / is / are / was / were** → **V4** (Continuous)

| Tense | Positive | Negative | Question |
| --- | --- | --- | --- |
| **Present Simple**<br>*(Routines, facts, regular work)* | **Sub + V1/V5**<br>I **work** on the backend.<br>The script **runs** nightly. | **Sub + do/does + not + V1**<br>I **don't work** on the UI.<br>It **doesn't support** REST. | **Do/Does + Sub + V1?**<br>**Do** you **work** on payments?<br>**Does** it **compile**? |
| **Present Continuous**<br>*(Happening now / around now)* | **Sub + am/is/are + V4**<br>I **am working** on the login.<br>We **are migrating** to AWS. | **Sub + am/is/are + not + V4**<br>I **am not working** on that.<br>They **aren't deploying** today. | **Am/Is/Are + Sub + V4?**<br>**Are** you **working** on the API?<br>**Is** the server **crashing**? |
| **Present Perfect**<br>*(Completed action relevant to now)* | **Sub + have/has + V3**<br>I **have completed** the API.<br>She **has pushed** the code. | **Sub + have/has + not + V3**<br>I **haven't completed** testing.<br>He **hasn't merged** the PR. | **Have/Has + Sub + V3?**<br>**Have** you **deployed** the fix?<br>**Has** the pipeline **failed**? |
| **Present Perfect Continuous**<br>*(Started in past, continuing now)* | **Sub + have/has + been + V4**<br>I **have been debugging** for hours.<br>It **has been failing** all day. | **Sub + have/has + not + been + V4**<br>I **haven't been working** on UI.<br>We **haven't been tracking** this. | **Have/Has + Sub + been + V4?**<br>**Have** you **been testing** it?<br>**Has** memory **been leaking**? |
| **Past Simple**<br>*(Completed action at finished time)* | **Sub + V2**<br>I **fixed** the bug yesterday.<br>The server **crashed** at 2 AM. | **Sub + did not + V1**<br>I **didn't find** the root cause.<br>We **didn't release** it. | **Did + Sub + V1?**<br>**Did** you **check** the logs?<br>**Did** the script **run**? |
| **Past Continuous**<br>*(In progress at a past time)* | **Sub + was/were + V4**<br>I **was debugging** when you called.<br>Tests **were running** slowly. | **Sub + was/were + not + V4**<br>I **wasn't monitoring** the DB.<br>They **weren't responding**. | **Was/Were + Sub + V4?**<br>What **were** you **doing**?<br>**Was** it **throwing** errors? |
| **Past Perfect**<br>*(Past action before another past action)*| **Sub + had + V3**<br>I **had completed** it before the sync.<br>Someone **had deleted** the file. | **Sub + had not + V3**<br>I **hadn't committed** the code yet.<br>We **hadn't tested** the edge case. | **Had + Sub + V3?**<br>**Had** you **checked** logs first?<br>**Had** the token **expired**? |
| **Past Perfect Continuous**<br>*(Ongoing past action before event)* | **Sub + had + been + V4**<br>I **had been trying** to fix it.<br>We **had been scaling** up nodes. | **Sub + had not + been + V4**<br>I **hadn't been looking** there.<br>It **hadn't been caching** properly. | **Had + Sub + been + V4?**<br>**Had** you **been waiting** long?<br>**Had** CPU **been spiking**? |
| **Future Simple**<br>*(Decision, promise, or prediction)* | **Sub + will + V1**<br>I **will fix** the issue today.<br>The job **will finish** soon. | **Sub + will not + V1**<br>I **won't deploy** without tests.<br>It **won't break** the build. | **Will + Sub + V1?**<br>**Will** you **join** the call?<br>**Will** the DB **scale**? |
| **Future Continuous**<br>*(In progress at a future time)* | **Sub + will + be + V4**<br>At 10 AM, I **will be coding**.<br>The script **will be executing**. | **Sub + will not + be + V4**<br>I **won't be working** tomorrow.<br>We **won't be accepting** traffic. | **Will + Sub + be + V4?**<br>**Will** you **be sharing** screen?<br>**Will** they **be migrating** data? |
| **Future Perfect**<br>*(Completed before a future point)* | **Sub + will + have + V3**<br>By Friday, I **will have finished**.<br>The sync **will have completed**. | **Sub + will not + have + V3**<br>She **won't have pushed** by then.<br>Data **won't have synced**. | **Will + Sub + have + V3?**<br>**Will** you **have merged** it?<br>**Will** the cache **have cleared**? |

---

### DO / DOES / DID / HAVE / HAS / BEEN

#### Common Error Corrections

* ❌ Does he **works** on the backend?
* ✅ Does he **work** on the backend? *(Does + V1)*

* ❌ Does the script **executes** automatically?
* ✅ Does the script **execute** automatically? *(Does + V1)*

* ❌ Did you **fixed** the bug?
* ✅ Did you **fix** the bug? *(Did + V1)*

* ❌ Did you **pushed** the hotfix?
* ✅ Did you **push** the hotfix? *(Did + V1)*

* ❌ Have you **complete** the task?
* ✅ Have you **completed** the task? *(Have + V3)*

* ❌ Have you **wrote** the integration tests?
* ✅ Have you **written** the integration tests? *(Have + V3)*

* ❌ Has she **deploy** the code?
* ✅ Has she **deployed** the code? *(Has + V3)*

* ❌ Has he **check** the logs?
* ✅ Has he **checked** the logs? *(Has + V3)*

* ❌ She has been **worked** on the UI module.
* ✅ She has been **working** on the UI module. *(Has been + V4)*

#### Usage Patterns

| Word / Pattern | Used For | Subject | What Comes After? | Positive Example | Negative Example | Question Example |
| --- | --- | --- | --- | --- | --- | --- |
| **DO** | Present Simple | I / You / We / They | **V1** | I **do agree**. | I **do not work**. | **Do** you **code**? |
| **DOES** | Present Simple | He / She / It | **V1** | It **does work**. | It **does not load**. | **Does** it **compile**? |
| **DID** | Past Simple | All subjects | **V1** | I **did test** it. | He **did not push**. | **Did** you **revert**? |
| **HAVE** | Present Perfect | I / You / We / They | **V3** | We **have merged**. | I **have not checked**. | **Have** you **synced**? |
| **HAS** | Present Perfect | He / She / It | **V3** | She **has reviewed**. | It **has not run**. | **Has** the job **failed**? |
| **HAD** | Past Perfect | All subjects | **V3** | I **had committed**. | We **had not planned**. | **Had** you **saved** it? |
| **HAVE BEEN** | Present Perf. Cont. | I / You / We / They | **V4** | I **have been debugging**. | We **have not been tracking**.| **Have** you **been waiting**? |
| **HAS BEEN** | Present Perf. Cont. | He / She / It | **V4** | It **has been leaking** RAM.| He **has not been coding**. | **Has** it **been failing**? |
| **HAD BEEN** | Past Perf. Cont. | All subjects | **V4** | We **had been scaling**. | I **had not been looking**. | **Had** he **been working**? |

---

### PREPOSITIONS

| Preposition | Main Use | Everyday Example | Tech / Software Example |
| --- | --- | --- | --- |
| **IN** | Inside / months / years / long periods | in the room, in July, in 2026 | The code is **in** the repository. The key is **in** the `.env` file. |
| **ON** | Surface / days / dates | on the table, on Monday | The app is running **on** port 8080. The service is hosted **on** AWS. |
| **AT** | Exact place / exact time | at home, at 5 PM | Set a breakpoint **at** line 42. The cron job triggers **at** midnight. |
| **TO** | Direction / destination | go to school, to Mumbai | Push your commits **to** the main branch. Connect **to** the database. |
| **FROM** | Starting point / source | from India, from Monday | Fetch the data **from** the REST API. Pull changes **from** upstream. |
| **FOR** | Duration / purpose | for 2 hours, for you | The server has been running **for** 72 hours. We use Redis **for** caching. |
| **SINCE** | Starting point in time | since Monday, since 2020 | The pod has been crash-looping **since** the last release. |
| **BY** | Deadline / method / agent | by 5 PM, by bus | Finish the code review **by** EOD. Data is sorted **by** timestamp. |
| **WITH** | Together / instrument | with me, with a knife | Authenticate **with** a bearer token. I pair-programmed **with** Alex. |
| **WITHOUT** | Absence | without money, without you | Do not deploy to prod **without** passing tests. |
| **OF** | Belonging / connection | color of the car | The latency **of** the query is high. An array **of** objects. |
| **ABOUT** | Topic / approximately | talk about work | Let's sync **about** the architecture. We have **about** 100ms latency. |
| **BEFORE** | Earlier than | before lunch, before 5 PM | Run local checks **before** opening a pull request. |
| **AFTER** | Later than | after work, after dinner | Re-run the suite **after** clearing the cache. |
| **DURING** | Within a period/event | during the meeting | CPU spiked **during** the batch processing job. |
| **UNTIL / TILL**| Up to a time | wait until 6 PM | Keep retrying **until** you receive a 200 OK. |
| **THROUGH** | From one side to another | through the door | Traffic flows **through** the API Gateway. |
| **ACROSS** | From one side to the other| across the road | Ensure consistent logging **across** all microservices. |
| **BETWEEN** | Two people/things | between A and B | Choose **between** REST and GraphQL. |
| **AMONG** | More than two / group | among friends | Load is distributed evenly **among** the three worker nodes. |
| **UNDER** | Lower than / state | under the table | The staging DB is currently **under** heavy load. |
| **OVER** | Above / covering / via | over the wall | We communicated the outage **over** Slack. |
| **BEHIND** | At the back of | behind the house | The service runs safely **behind** a reverse proxy. |
| **IN FRONT OF** | Before / ahead of | in front of the car | Place a CDN **in front of** the S3 bucket to improve speed. |
| **BESIDE** | Next to | beside me | Keep the README file **beside** the codebase root. |
| **NEAR** | Close to | near the station | Route traffic to the edge server **near** the user. |
| **INTO** | Movement → inside | go into the room | Insert new user records **into** the database table. |
| **ONTO** | Movement → surface | jump onto the table | Stream live logs **onto** the centralized dashboard. |
| **OUT OF** | Movement → outside | come out of the room | The container ran **out of** memory (OOM). |
| **TOWARD(S)** | Direction | walk towards the door | We are moving **towards** an event-driven architecture. |

#### Common Preposition Pairs in Action

* **TO vs. INTO**:
    * Navigate **to** the dashboard page. *(Destination)*
    * Inject dependencies **into** the constructor. *(Movement inside)*
* **IN vs. INTO**:
    * The data is stored **in** the table. *(Already inside)*
    * Parse the JSON response **into** a TypeScript interface. *(Transformation)*
* **ON vs. ONTO**:
    * The feature flag is enabled **on** production. *(State / Surface)*
    * Deploy the compiled build **onto** the staging server. *(Action onto surface)*
* **BETWEEN vs. AMONG**:
    * There is a disconnect **between** the client and server. *(Two entities)*
    * Divide the workload **among** the team members. *(Group)*
* **BESIDE vs. BESIDES**:
    * Sit **beside** me during the system demo. *(Next to)*
    * **Besides** backend work, are you handling migrations? *(In addition to)*

---

### ENGLISH MODAL VERBS

| Modal | Main Use | Meaning | Verb Form | Negative | Question | IT Example |
| --- | --- | --- | --- | --- | --- | --- |
| **CAN** | Ability / permission | able to / allowed | V1 | cannot / can't | Can + S + V1? | The user **can access** the dashboard. |
| **COULD** | Past ability / polite request | was able / polite | V1 | couldn't | Could + S + V1? | **Could** you **review** my PR? |
| **MAY** | Permission / possibility | allowed / possible | V1 | may not | May + S + V1? | We **may experience** downtime. |
| **MIGHT** | Weak possibility | perhaps | V1 | might not | Might + S + V1? | The deployment **might fail**. |
| **MUST** | Strong obligation / certainty | have to / certainly | V1 | must not | Must + S + V1? | We **must encrypt** the passwords. |
| **SHOULD** | Advice / expectation | ought to | V1 | shouldn't | Should + S + V1? | You **should write** unit tests. |
| **WOULD** | Polite / hypothetical | polite / imagined | V1 | wouldn't | Would + S + V1? | I **would prefer** caching this. |
| **WILL** | Future / willingness | future / ready | V1 | won't | Will + S + V1? | The script **will run** at midnight. |
| **SHALL** | Suggestion / offer | let us / will | V1 | shan't | Shall + S + V1? | **Shall we rollback** the release? |
| **HAVE TO** | Necessity / obligation | need to | V1 | don't have to | Do/Does + S + have to? | We **have to patch** this vulnerability. |
| **NEED TO** | Necessity | require | V1 | don't need to | Do/Does + S + need to? | I **need to debug** the webhook. |

---

### PROFESSIONAL PHRASES & COMMUNICATION
### 1. Standup Facilitation, Flow & Timeboxing

#### Meeting Kickoff & Facilitation

* "Good morning, everyone. Let's get started. We'll go through everyone's updates one by one. Let's start with Rahul."
* "Rahul, could you give us a quick update on what you worked on yesterday?"
* "What are you planning to work on today?"
* "Do you have any blockers or issues?"
* "John, could you share your thoughts on this?"
* "Does anyone else have any input?"

#### Transitions & Flow

* "Okay, sounds good. Let's move on."
* "Let's move on to the next update."
* "If there are no further questions, let me move on to the next item."
* "Thanks, Rahul. If there are no further questions, let's move on to Priya."

#### Timeboxing & Taking Discussions Offline

* "This seems like a deeper architecture discussion—let's take this offline after the standup."
* "Could we take that discussion offline and come back to today's agenda?"
* "Let's note that down and discuss it separately after the DSM."
* "Let's create a quick sync on Slack after the call so we don't block the rest of the DSM."
* "In the interest of time, let's defer that discussion to our tech design review."

#### Wrapping Up

* "Okay, I think that's everything for today."
* "Are there any other points we need to discuss? If there are no other points, we'll wrap up here."
* "Thanks, everyone. Have a great day."

---

### 2. Daily Standup Updates & Task Confirmation

#### Standard Daily Updates (Past, Present, Blockers)

* "Yesterday, I worked on the authentication API. Today, I'll continue working on it. I don't have any blockers."
* "Yesterday, I worked on indexing the primary tables. Today, I'll complete the SQL scripts. No blockers on my end."
* "Yesterday, I set up the Redis cache. Today, I'm working on unit tests. I'm currently blocked by AWS access permissions."
* "I spent yesterday debugging the CI/CD pipeline failure. Today, I'll push the updated YAML configuration."
* "I am currently blocked by AWS IAM permissions. Could someone from DevOps help me out?"
* "Sure. I'll update the payment API, test the changes, and deploy them to staging."

#### Confirming Understanding & Paraphrasing

* "Just to make sure I understand, are you saying that...?"
* "Could you clarify what you mean by...?"
* "So, you're saying that we need to deploy the API before Friday, correct?"
* "If I understood correctly, the issue is related to the database connection. Just to confirm, you want me to update the API and deploy it to staging, correct?"
* "Let me make sure I understood correctly. You want us to remove the old authentication flow, right?"
* "So, the requirement is to support both OAuth and password authentication. Is that correct?"
* "Sure. Just to confirm, I need to update the payment API, test it, and deploy it to staging. Is that correct?"
* "Just to confirm, the authentication API is still on track for tomorrow, correct?"
* "Just to confirm, you want me to deprecate the old endpoints, correct?"

---

### 3. Status Probing, Uncovering Blockers & Offering Support

#### Asking for Task Details & Progress

* "Could you give us a little more detail about what you worked on?"
* "Which part of the API did you work on?"
* "How is it progressing?"
* "Do you expect any delays?"
* "When do you expect to complete it?"
* "Is it completed, or is there anything remaining?"
* "Is the issue resolved now, or is there anything remaining?"
* "Have you identified the root cause yet?"
* "Can you update the payment API and deploy it to staging?"

#### Exploring Blockers & Offering Support

* "Could you give us a little more detail about the blocker?"
* "Could you give us a little more detail about the payment issue?"
* "What seems to be blocking you?"
* "Could you explain what is blocking the task?"
* "Is anything blocking you from completing it?"
* "Do you need any help from the team?"
* "Is there anything we can do to help?"
* "Do you need help from the backend team?"
* "What can we do to unblock you?"

---

### 4. Technical Clarifications & System Design

#### General Technical Clarifications

* "Could you please explain how this API works?"
* "Could you please provide more details about the deployment issue?"
* "Could you please clarify what you mean by 'the old flow'?"
* "Could you give me an example of the expected response?"
* "Could you provide an example of the expected JSON payload?"
* "Could you walk me through the current authentication flow?"
* "Could you elaborate on the database issue?"
* "Could you elaborate on the database migration strategy?"
* "Could you help me understand why we need this change?"
* "Could you explain how this service communicates with the payment service?"
* "Could you explain that in a little more detail?"
* "I'm not completely clear on that. Could you explain it again?"
* "I understand the overall idea, but could you clarify how the second step works?"
* "I understand the overall idea, but could you clarify how the fallback mechanism works?"
* "Could you explain the approach to the team?"
* "Could you take us through the implementation?"

#### Specific Technical Questions

* "Could you walk me through how edge cases are handled in this module?"
* "Could you clarify whether this fix applies to both web and mobile?"
* "Could you provide an example of the expected payload structure?"
* "I understand the high-level design, but could you elaborate on the database migration step?"

---

### 5. Code Reviews & Pull Requests (PRs)

* "Could you add a unit test for this edge case?"
* "I left a few comments on the PR regarding variable naming."
* "Could we extract this logic into a separate utility function?"
* "This looks good to me (LGTM). Approving."
* "Can you rebase this branch onto `main` to resolve the conflicts?"
* "I see where you're coming from, but wouldn't async processing be more resilient here?"

---

### 6. Incident Management, Operations & Uncertainty

#### Incidents & System Operations

* "We are currently investigating a spike in API latency."
* "The system is degrading; I am initiating a rollback to the previous stable version."
* "I'll check with the infrastructure team and update the incident channel."

#### Managing Uncertainty & Verification

* "I'm not sure about that. Let me check and get back to you."
* "I don't have that information right now."
* "I'll confirm and get back to you."
* "I'm not completely sure."
* "Let me verify it first."
* "I'll check with the team and update you."
* "I'm not completely sure about the root cause yet."
* "I'm not sure about the root cause yet. Let me check the logs and get back to you."
* "Let me think about that for a moment."
* "Let me check that. Give me a moment to verify that."
* "Let me look into it and get back to you."
* "I'll need to check the implementation before I can confirm."
* "Let me verify the database metrics before I confirm."

---

### 7. Expressing Agreement & Technical Alternatives

#### Expressing Agreement

* "That's an important point."
* "That makes sense. I agree with that approach."
* "I think that's a good approach."
* "Yes, I think that would work."
* "That makes sense. I'll adopt that pattern in my pull request."

#### Suggesting Alternatives & Feedback

* "I see your point, but I think there may be another approach."
* "I understand what you mean. However, I think we should consider another option."
* "I'm not sure I completely agree with that."
* "I have a slightly different view on this."
* "Could we also consider this approach?"
* "I understand your point. However, I think caching the response might be better than making a database query every time."
* "I think we should... / I would suggest... / I would suggest moving this validation to the service layer."
* "I see where you're coming from, but wouldn't async processing be more resilient here?"
* "That's a valid approach, though I'd suggest using Redis to keep response latency low."
* "I agree with the proposed design, but we should make sure rate limiting is enforced."

---

### 8. Meetings, Audio, Screen Sharing & Polite Interruptions

#### Audio & Connection Issues

* "Sorry, could you repeat that, please?"
* "Sorry, I didn't catch that. Could you say that again?"
* "Sorry, could you please repeat the last part?"
* "I missed the last part. Could you please repeat it?"
* "Sorry, your audio broke up for a moment. Could you please repeat that?"
* "Sorry, your audio cut out for a second. Could you repeat the part about the deployment time?"

#### Screen Sharing

* "My screen is loading. Can everyone see my IDE now?"
* "Sorry to interrupt, but your screen froze while showing the terminal. Could you re-share?"

#### Interrupting Politely

* "Sorry for interrupting. Could I ask a quick question?"
* "Before we move on, could I clarify one point?"
* "Sorry to interrupt, but I just want to clarify one thing."
