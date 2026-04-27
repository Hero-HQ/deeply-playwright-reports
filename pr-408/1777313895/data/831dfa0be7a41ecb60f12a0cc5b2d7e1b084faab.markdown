# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: pr-408-sort-happy-path.spec.ts >> PR-408 Sort — Happy Path & Date Created correctness >> A.1 Sort by Urgency: dropdown opens with all options, label updates, dropdown closes
- Location: tests/pr-408-sort-happy-path.spec.ts:12:7

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: getByRole('button', { name: 'Date created' }).last().locator('img')
Expected: visible
Timeout: 5000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 5000ms
  - waiting for getByRole('button', { name: 'Date created' }).last().locator('img')

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e2]:
    - complementary [ref=e3]:
      - generic [ref=e5]:
        - link "Deeply" [ref=e6] [cursor=pointer]:
          - /url: /dashboard
          - img [ref=e7]
          - generic [ref=e9]: Deeply
        - button "Close sidebar" [ref=e10] [cursor=pointer]:
          - img [ref=e11]
      - navigation [ref=e13]:
        - button "Home" [ref=e14] [cursor=pointer]:
          - img [ref=e16]
          - generic [ref=e19]: Home
        - button "Issues" [ref=e20] [cursor=pointer]:
          - img [ref=e22]
          - generic [ref=e25]: Issues
        - button "Commitments" [ref=e26] [cursor=pointer]:
          - img [ref=e28]
          - generic [ref=e31]: Commitments
        - button "Chat" [ref=e32] [cursor=pointer]:
          - img [ref=e34]
          - generic [ref=e36]: Chat
        - button "Reminders" [ref=e37] [cursor=pointer]:
          - img [ref=e39]
          - generic [ref=e42]: Reminders
        - button "Profile" [ref=e43] [cursor=pointer]:
          - img [ref=e45]
          - generic [ref=e48]: Profile
        - generic [ref=e49]:
          - generic [ref=e50]: Recents
          - generic [ref=e51]:
            - button "Untitled" [ref=e52] [cursor=pointer]:
              - generic "Untitled" [ref=e53]
            - button "Conversation options" [ref=e54] [cursor=pointer]:
              - img [ref=e55]
          - generic [ref=e59]:
            - button "Untitled" [ref=e60] [cursor=pointer]:
              - generic "Untitled" [ref=e61]
            - button "Conversation options" [ref=e62] [cursor=pointer]:
              - img [ref=e63]
          - generic [ref=e67]:
            - button "Untitled" [ref=e68] [cursor=pointer]:
              - generic "Untitled" [ref=e69]
            - button "Conversation options" [ref=e70] [cursor=pointer]:
              - img [ref=e71]
          - generic [ref=e75]:
            - button "Untitled" [ref=e76] [cursor=pointer]:
              - generic "Untitled" [ref=e77]
            - button "Conversation options" [ref=e78] [cursor=pointer]:
              - img [ref=e79]
          - generic [ref=e83]:
            - button "Untitled" [ref=e84] [cursor=pointer]:
              - generic "Untitled" [ref=e85]
            - button "Conversation options" [ref=e86] [cursor=pointer]:
              - img [ref=e87]
          - generic [ref=e91]:
            - button "Untitled" [ref=e92] [cursor=pointer]:
              - generic "Untitled" [ref=e93]
            - button "Conversation options" [ref=e94] [cursor=pointer]:
              - img [ref=e95]
          - generic [ref=e99]:
            - button "Untitled" [ref=e100] [cursor=pointer]:
              - generic "Untitled" [ref=e101]
            - button "Conversation options" [ref=e102] [cursor=pointer]:
              - img [ref=e103]
          - generic [ref=e107]:
            - button "Untitled" [ref=e108] [cursor=pointer]:
              - generic "Untitled" [ref=e109]
            - button "Conversation options" [ref=e110] [cursor=pointer]:
              - img [ref=e111]
          - generic [ref=e115]:
            - button "Untitled" [ref=e116] [cursor=pointer]:
              - generic "Untitled" [ref=e117]
            - button "Conversation options" [ref=e118] [cursor=pointer]:
              - img [ref=e119]
          - generic [ref=e123]:
            - button "Untitled" [ref=e124] [cursor=pointer]:
              - generic "Untitled" [ref=e125]
            - button "Conversation options" [ref=e126] [cursor=pointer]:
              - img [ref=e127]
          - generic [ref=e131]:
            - button "Untitled" [ref=e132] [cursor=pointer]:
              - generic "Untitled" [ref=e133]
            - button "Conversation options" [ref=e134] [cursor=pointer]:
              - img [ref=e135]
          - generic [ref=e139]:
            - button "Untitled" [ref=e140] [cursor=pointer]:
              - generic "Untitled" [ref=e141]
            - button "Conversation options" [ref=e142] [cursor=pointer]:
              - img [ref=e143]
          - generic [ref=e147]:
            - button "Untitled" [ref=e148] [cursor=pointer]:
              - generic "Untitled" [ref=e149]
            - button "Conversation options" [ref=e150] [cursor=pointer]:
              - img [ref=e151]
          - generic [ref=e155]:
            - button "Untitled" [ref=e156] [cursor=pointer]:
              - generic "Untitled" [ref=e157]
            - button "Conversation options" [ref=e158] [cursor=pointer]:
              - img [ref=e159]
          - generic [ref=e163]:
            - button "Decision-making friction in …" [ref=e164] [cursor=pointer]:
              - generic "Decision-making friction in our relationship" [ref=e165]: Decision-making friction in …
            - button "Conversation options" [ref=e166] [cursor=pointer]:
              - img [ref=e167]
          - generic [ref=e171]:
            - button "Untitled" [ref=e172] [cursor=pointer]:
              - generic "Untitled" [ref=e173]
            - button "Conversation options" [ref=e174] [cursor=pointer]:
              - img [ref=e175]
          - generic [ref=e179]:
            - button "Untitled" [ref=e180] [cursor=pointer]:
              - generic "Untitled" [ref=e181]
            - button "Conversation options" [ref=e182] [cursor=pointer]:
              - img [ref=e183]
          - generic [ref=e187]:
            - button "Untitled" [ref=e188] [cursor=pointer]:
              - generic "Untitled" [ref=e189]
            - button "Conversation options" [ref=e190] [cursor=pointer]:
              - img [ref=e191]
          - generic [ref=e195]:
            - button "Untitled" [ref=e196] [cursor=pointer]:
              - generic "Untitled" [ref=e197]
            - button "Conversation options" [ref=e198] [cursor=pointer]:
              - img [ref=e199]
          - generic [ref=e203]:
            - button "How we make decisions togeth…" [ref=e204] [cursor=pointer]:
              - generic "How we make decisions together" [ref=e205]: How we make decisions togeth…
            - button "Conversation options" [ref=e206] [cursor=pointer]:
              - img [ref=e207]
          - generic [ref=e211]:
            - button "Decision-making friction in …" [ref=e212] [cursor=pointer]:
              - generic "Decision-making friction in our relationship" [ref=e213]: Decision-making friction in …
            - button "Conversation options" [ref=e214] [cursor=pointer]:
              - img [ref=e215]
          - generic [ref=e219]:
            - 'button "QA: persistent input test" [ref=e220] [cursor=pointer]':
              - 'generic "QA: persistent input test" [ref=e221]'
            - button "Conversation options" [ref=e222] [cursor=pointer]:
              - img [ref=e223]
          - generic [ref=e227]:
            - button "We keep arguing about the sa…" [ref=e228] [cursor=pointer]:
              - generic "We keep arguing about the same things" [ref=e229]: We keep arguing about the sa…
            - button "Conversation options" [ref=e230] [cursor=pointer]:
              - img [ref=e231]
      - button "Q QA Agent with Partner B" [ref=e236] [cursor=pointer]:
        - generic [ref=e237]: Q
        - generic [ref=e238]:
          - generic [ref=e239]: QA Agent
          - generic [ref=e240]: with Partner B
        - img [ref=e241]
    - generic [ref=e244]:
      - generic [ref=e245]:
        - button "Open menu" [ref=e246] [cursor=pointer]:
          - img [ref=e247]
        - link "Deeply" [ref=e249] [cursor=pointer]:
          - /url: /dashboard
          - img [ref=e250]
          - generic [ref=e252]: Deeply
      - link "Q" [ref=e253] [cursor=pointer]:
        - /url: /settings
        - generic [ref=e254]: Q
    - main [ref=e255]:
      - generic [ref=e256]:
        - generic [ref=e257]:
          - generic [ref=e258]:
            - generic [ref=e259]:
              - heading "My Issues" [level=1] [ref=e260]
              - link "+ New conversation" [ref=e261] [cursor=pointer]:
                - /url: /chat
            - generic [ref=e262]:
              - button "Sort issues" [expanded] [active] [ref=e263] [cursor=pointer]:
                - img [ref=e264]
                - generic [ref=e265]: Date created
                - img [ref=e266]
              - generic [ref=e269]:
                - button "Urgency" [ref=e270] [cursor=pointer]
                - button "Importance" [ref=e271] [cursor=pointer]
                - button "Date created" [ref=e272] [cursor=pointer]:
                  - text: Date created
                  - img [ref=e273]
          - generic [ref=e275]:
            - button "Board" [ref=e276] [cursor=pointer]
            - button "List" [ref=e277] [cursor=pointer]
            - button "Matrix" [ref=e278] [cursor=pointer]
        - generic [ref=e281]:
          - generic [ref=e282]:
            - generic [ref=e284]:
              - generic [ref=e286]: New
              - generic [ref=e287]: "18"
            - generic [ref=e288]:
              - generic [ref=e289] [cursor=pointer]:
                - generic [ref=e290]:
                  - generic [ref=e291]: Communication
                  - generic [ref=e292]:
                    - generic [ref=e293]: 🔒
                    - text: Private
                - paragraph [ref=e294]: QA Test Issue
                - paragraph [ref=e295]: This issue was created by the QA seed script for automated testing.
                - generic [ref=e296]:
                  - generic [ref=e297]: Apr 27
                  - button "Work through this" [ref=e298]
              - generic [ref=e299] [cursor=pointer]:
                - generic [ref=e301]:
                  - generic [ref=e302]: 🔒
                  - text: Private
                - paragraph [ref=e303]: Fresh Issue No Nudge Test
                - generic [ref=e304]: Haven’t touched this in 5 days
                - generic [ref=e305]:
                  - generic [ref=e306]: Apr 24
                  - button "Work through this" [ref=e307]
              - generic [ref=e308] [cursor=pointer]:
                - generic [ref=e310]:
                  - generic [ref=e311]: 🔒
                  - text: Private
                - paragraph [ref=e312]: Staleness Nudge Test Issue - Kanban
                - generic [ref=e313]: Haven’t touched this in 17 days
                - generic [ref=e314]:
                  - generic [ref=e315]: Apr 24
                  - button "Work through this" [ref=e316]
              - generic [ref=e317] [cursor=pointer]:
                - generic [ref=e319]:
                  - generic [ref=e320]: 🔒
                  - text: Private
                - paragraph [ref=e321]: Fresh Proof Issue — just started
                - generic [ref=e322]:
                  - generic [ref=e323]: Apr 24
                  - button "Work through this" [ref=e324]
              - generic [ref=e325] [cursor=pointer]:
                - generic [ref=e327]:
                  - generic [ref=e328]: 🔒
                  - text: Private
                - paragraph [ref=e329]: QA Fresh Issue - No Staleness Nudge
                - generic [ref=e330]:
                  - generic [ref=e331]: Apr 24
                  - button "Work through this" [ref=e332]
              - generic [ref=e333] [cursor=pointer]:
                - generic [ref=e335]:
                  - generic [ref=e336]: 🔒
                  - text: Private
                - paragraph [ref=e337]: QA Fresh Issue - No Staleness Nudge
                - generic [ref=e338]:
                  - generic [ref=e339]: Apr 24
                  - button "Work through this" [ref=e340]
              - generic [ref=e341] [cursor=pointer]:
                - generic [ref=e343]:
                  - img [ref=e344]
                  - text: Shared
                - paragraph [ref=e347]: Future Goals — Joint (Viewer)
                - generic [ref=e348]:
                  - generic [ref=e349]: Apr 22
                  - button "Work through this" [ref=e350]
              - generic [ref=e351] [cursor=pointer]:
                - generic [ref=e353]:
                  - img [ref=e354]
                  - text: Shared
                - paragraph [ref=e357]: Conflict Resolution — Joint (Editor)
                - paragraph [ref=e358]: "# Summary You've identified a conflict that needs resolving between both of you, and the next step is to add some details about what's happening so you can work through it together with clarity and care."
                - generic [ref=e359]:
                  - generic [ref=e360]: Apr 22
                  - button "Work through this" [ref=e361]
              - generic [ref=e362] [cursor=pointer]:
                - generic [ref=e364]:
                  - img [ref=e365]
                  - text: Shared
                - paragraph [ref=e368]: Decision Making — Shared (Editor)
                - paragraph [ref=e369]: It sounds like you've identified that decision-making feels shared when you'd prefer clearer roles—the next step is to jot down a specific example of a decision that felt unclear, so you can explore together what "owned" decision-making would look like for you both.
                - generic [ref=e370]:
                  - generic [ref=e371]: Apr 22
                  - button "Work through this" [ref=e372]
              - generic [ref=e373] [cursor=pointer]:
                - generic [ref=e375]:
                  - img [ref=e376]
                  - text: Shared
                - paragraph [ref=e379]: Trust & Openness — Shared (Viewer)
                - paragraph [ref=e380]: "# Summary You've identified trust and openness as something you'd like to work on together, and the next step is to have a gentle conversation where you both share what's on your minds—maybe starting with what \"trust and openness\" means to each of you and where you're feeling a gap."
                - generic [ref=e381]:
                  - generic [ref=e382]: Apr 22
                  - button "Work through this" [ref=e383]
              - generic [ref=e384] [cursor=pointer]:
                - generic [ref=e386]:
                  - generic [ref=e387]: 🔒
                  - text: Private
                - paragraph [ref=e388]: Communication Pattern — Private
                - paragraph [ref=e389]: It sounds like you've identified that communication patterns might be affecting your relationship, and the next step would be to jot down some specific examples of what's been happening so you can clarify what you'd like to improve together.
                - generic [ref=e390]:
                  - generic [ref=e391]: Apr 22
                  - button "Work through this" [ref=e392]
              - generic [ref=e393] [cursor=pointer]:
                - generic [ref=e395]:
                  - img [ref=e396]
                  - text: Shared
                - paragraph [ref=e399]: Joint Issue - Viewer
                - generic [ref=e400]:
                  - generic [ref=e401]: Apr 22
                  - button "Work through this" [ref=e402]
              - generic [ref=e403] [cursor=pointer]:
                - generic [ref=e405]:
                  - img [ref=e406]
                  - text: Shared
                - paragraph [ref=e409]: Joint Issue - Editor
                - paragraph [ref=e410]: "# Summary You and your partner have identified a concern about your editor, but haven't yet discussed the specifics together—a conversation to align on what's bothering you both would be a caring and practical first step."
                - generic [ref=e411]:
                  - generic [ref=e412]: Apr 22
                  - button "Work through this" [ref=e413]
              - generic [ref=e414] [cursor=pointer]:
                - generic [ref=e416]:
                  - img [ref=e417]
                  - text: Shared
                - paragraph [ref=e420]: Shared - Editor Role
                - paragraph [ref=e421]: "# Summary You've identified a concern about shared editor access, but we need more details about what's happening—let's start by understanding whether this is about permissions not working as expected, unclear role boundaries, or something else entirely, so we can help you resolve it together."
                - generic [ref=e422]:
                  - generic [ref=e423]: Apr 22
                  - button "Work through this" [ref=e424]
              - generic [ref=e425] [cursor=pointer]:
                - generic [ref=e427]:
                  - img [ref=e428]
                  - text: Shared
                - paragraph [ref=e431]: Shared - Viewer Role
                - paragraph [ref=e432]: It sounds like you're working through a permissions question about shared viewing access, and the next step would be to add some details about what you're trying to accomplish so we can help you find the best solution together.
                - generic [ref=e433]:
                  - generic [ref=e434]: Apr 22
                  - button "Work through this" [ref=e435]
              - generic [ref=e436] [cursor=pointer]:
                - generic [ref=e438]:
                  - generic [ref=e439]: 🔒
                  - text: Private
                - paragraph [ref=e440]: Private Test Issue - Lifecycle
                - paragraph [ref=e441]: "# Summary You've just created this issue to test the lifecycle process, and the next step is to add details about what you'd like to track so we can move forward together!"
                - generic [ref=e442]:
                  - generic [ref=e443]: Apr 22
                  - button "Work through this" [ref=e444]
              - generic [ref=e445] [cursor=pointer]:
                - generic [ref=e446]:
                  - generic [ref=e447]: Communication
                  - generic [ref=e448]:
                    - img [ref=e449]
                    - text: Shared
                - paragraph [ref=e452]: We keep having the same argument
                - generic [ref=e453]:
                  - generic [ref=e454]: Apr 22
                  - button "Work through this" [ref=e455]
              - generic [ref=e456] [cursor=pointer]:
                - generic [ref=e458]:
                  - generic [ref=e459]: 🔒
                  - text: Private
                - paragraph [ref=e460]: Stale Proof Issue — 5 days untouched
                - generic [ref=e461]: Haven’t touched this in 8 days
                - generic [ref=e462]:
                  - generic [ref=e463]: Apr 19
                  - button "Work through this" [ref=e464]
          - generic [ref=e465]:
            - generic [ref=e467]:
              - generic [ref=e469]: Working on it
              - generic [ref=e470]: "7"
            - generic [ref=e471]:
              - generic [ref=e472] [cursor=pointer]:
                - generic [ref=e474]:
                  - generic [ref=e475]: 🔒
                  - text: Private
                - paragraph [ref=e476]: Staleness Nudge Test Issue - Resolving
                - generic [ref=e477]: Haven’t touched this in 17 days
                - generic [ref=e478]:
                  - generic [ref=e479]: Updated Apr 10
                  - button "Continue" [ref=e480]
              - generic [ref=e481] [cursor=pointer]:
                - generic [ref=e483]:
                  - generic [ref=e484]: 🔒
                  - text: Private
                - paragraph [ref=e485]: QA Stale Issue - Staleness Nudge Test
                - generic [ref=e486]:
                  - generic [ref=e487]: Updated Apr 24
                  - button "Continue" [ref=e488]
              - generic [ref=e489] [cursor=pointer]:
                - generic [ref=e491]:
                  - generic [ref=e492]: 🔒
                  - text: Private
                - paragraph [ref=e493]: QA Stale Issue - Staleness Nudge Test
                - generic [ref=e494]:
                  - generic [ref=e495]: Updated Apr 24
                  - button "Continue" [ref=e496]
              - generic [ref=e497] [cursor=pointer]:
                - generic [ref=e499]:
                  - generic [ref=e500]: 🔒
                  - text: Private
                - paragraph [ref=e501]: QA Nav Fix Test Issue
                - paragraph [ref=e502]: "# Summary This QA navigation fix is ready for you to add details that describe what needs testing — once you fill those in, the team can start working on it."
                - generic [ref=e503]:
                  - generic [ref=e504]: Updated Apr 24
                  - button "Continue" [ref=e505]
              - generic [ref=e506] [cursor=pointer]:
                - generic [ref=e508]:
                  - img [ref=e509]
                  - text: Shared
                - paragraph [ref=e512]: QA Partner Role Test Issue (Shared/Resolving)
                - paragraph [ref=e513]: "# Summary It sounds like you're exploring a QA partner role and are just getting started—next, it would help to add some details about what you're testing or what specific partnership dynamic you'd like feedback on."
                - generic [ref=e514]:
                  - generic [ref=e515]: Updated Apr 24
                  - button "Continue" [ref=e516]
              - generic [ref=e517] [cursor=pointer]:
                - generic [ref=e519]:
                  - img [ref=e520]
                  - text: Shared
                - paragraph [ref=e523]: QA Scope Removal Test Issue
                - paragraph [ref=e524]: "# Summary It looks like this issue needs some love—there are no details yet, so the next step is to add specifics about what QA scope is being removed and why, which will help clarify the path forward."
                - generic [ref=e525]:
                  - generic [ref=e526]: Updated Apr 24
                  - button "Continue" [ref=e527]
              - generic [ref=e528] [cursor=pointer]:
                - generic [ref=e530]:
                  - generic [ref=e531]: 🔒
                  - text: Private
                - paragraph [ref=e532]: QA Hydration Test Issue
                - generic [ref=e533]:
                  - generic [ref=e534]: Updated Apr 24
                  - button "Continue" [ref=e535]
          - generic [ref=e536]:
            - generic [ref=e538]:
              - generic [ref=e540]: Resolved
              - generic [ref=e541]: "2"
            - generic [ref=e542]:
              - generic [ref=e543] [cursor=pointer]:
                - generic [ref=e545]:
                  - generic [ref=e546]: 🔒
                  - text: Private
                - paragraph [ref=e547]: Resolved Issue No Nudge Test
                - generic [ref=e548]:
                  - generic [ref=e549]: Resolved Apr 10
                  - button "View" [ref=e550]
              - generic [ref=e551] [cursor=pointer]:
                - generic [ref=e553]:
                  - img [ref=e554]
                  - text: Shared
                - paragraph [ref=e557]: QA Partner Role Test Issue (Shared/Resolved)
                - generic [ref=e558]:
                  - generic [ref=e559]: Resolved Apr 23
                  - button "View" [ref=e560]
  - alert [ref=e561]
  - iframe [ref=e562]:
    
  - button "Open Intercom Messenger" [ref=e563] [cursor=pointer]:
    - img [ref=e565]
    - generic:
      - img
```

# Test source

```ts
  1   | import { test, expect } from "@playwright/test";
  2   | 
  3   | test.describe("PR-408 Sort — Happy Path & Date Created correctness", () => {
  4   |   test.beforeEach(async ({ page }) => {
  5   |     await page.goto("/issues");
  6   |     await page.evaluate(() => localStorage.clear());
  7   |     await page.reload();
  8   |     await expect(page.getByRole("button", { name: "Sort issues" })).toBeVisible();
  9   |   });
  10  | 
  11  |   // A.1 — Sort by Urgency
  12  |   test("A.1 Sort by Urgency: dropdown opens with all options, label updates, dropdown closes", async ({ page }) => {
  13  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  14  | 
  15  |     // Default label is Date created
  16  |     await expect(sortBtn).toContainText("Date created");
  17  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  18  | 
  19  |     // Open dropdown
  20  |     await sortBtn.click();
  21  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "true");
  22  | 
  23  |     // All three options visible
  24  |     await expect(page.getByRole("button", { name: "Urgency" })).toBeVisible();
  25  |     await expect(page.getByRole("button", { name: "Importance" })).toBeVisible();
  26  |     // Use last() to distinguish dropdown option from any other text
  27  |     const dateCreatedOption = page.getByRole("button", { name: "Date created" }).last();
  28  |     await expect(dateCreatedOption).toBeVisible();
  29  | 
  30  |     // Active option (Date created) has checkmark img
> 31  |     await expect(dateCreatedOption.locator("img")).toBeVisible();
      |                                                    ^ Error: expect(locator).toBeVisible() failed
  32  |     // Urgency option has no checkmark
  33  |     await expect(page.getByRole("button", { name: "Urgency" }).locator("img")).not.toBeAttached();
  34  | 
  35  |     // Select Urgency
  36  |     await page.getByRole("button", { name: "Urgency" }).click();
  37  | 
  38  |     // Dropdown closes
  39  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  40  |     await expect(page.getByRole("button", { name: "Urgency" })).not.toBeVisible();
  41  | 
  42  |     // Button label updates
  43  |     await expect(sortBtn).toContainText("Urgency");
  44  | 
  45  |     // Board columns still present
  46  |     await expect(page.getByText("New")).toBeVisible();
  47  |     await expect(page.getByText("Working on it")).toBeVisible();
  48  |     await expect(page.getByText("Resolved")).toBeVisible();
  49  |   });
  50  | 
  51  |   // A.2 — Sort by Importance
  52  |   test("A.2 Sort by Importance: button label updates, board remains intact", async ({ page }) => {
  53  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  54  | 
  55  |     await sortBtn.click();
  56  |     await expect(page.getByRole("button", { name: "Importance" })).toBeVisible();
  57  |     await page.getByRole("button", { name: "Importance" }).click();
  58  | 
  59  |     // Dropdown closes
  60  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  61  | 
  62  |     // Button label updates
  63  |     await expect(sortBtn).toContainText("Importance");
  64  | 
  65  |     // Board still renders with columns
  66  |     await expect(page.getByText("New")).toBeVisible();
  67  |   });
  68  | 
  69  |   // A.2 continued — checkmark moves to active option after selection
  70  |   test("A.2 Checkmark moves to newly selected sort option in re-opened dropdown", async ({ page }) => {
  71  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  72  | 
  73  |     // Select Importance
  74  |     await sortBtn.click();
  75  |     await page.getByRole("button", { name: "Importance" }).click();
  76  | 
  77  |     // Re-open dropdown
  78  |     await sortBtn.click();
  79  | 
  80  |     // Importance should now have checkmark
  81  |     await expect(
  82  |       page.getByRole("button", { name: "Importance" }).locator("img")
  83  |     ).toBeVisible();
  84  | 
  85  |     // Urgency should not have checkmark
  86  |     await expect(
  87  |       page.getByRole("button", { name: "Urgency" }).locator("img")
  88  |     ).not.toBeAttached();
  89  |   });
  90  | 
  91  |   // F.1 — Date Created sort shows newest first
  92  |   test("F.1 Default Date created sort shows QA Test Issue (Apr 27) before older issues", async ({ page }) => {
  93  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  94  | 
  95  |     // Default sort is Date created (newest first)
  96  |     await expect(sortBtn).toContainText("Date created");
  97  | 
  98  |     // QA Test Issue (Apr 27) is the seeded newest issue — it must be visible
  99  |     await expect(page.getByText("QA Test Issue")).toBeVisible();
  100 | 
  101 |     // Verify it appears before older issues by comparing bounding boxes
  102 |     const newestCard = page.getByText("QA Test Issue");
  103 |     const olderCard = page.getByText("Stale Proof Issue — 5 days untouched");
  104 | 
  105 |     await expect(newestCard).toBeVisible();
  106 |     await expect(olderCard).toBeVisible();
  107 | 
  108 |     const newestBox = await newestCard.boundingBox();
  109 |     const olderBox = await olderCard.boundingBox();
  110 | 
  111 |     expect(newestBox).not.toBeNull();
  112 |     expect(olderBox).not.toBeNull();
  113 |     // Newest (Apr 27) should have a smaller Y value (appears higher) than Apr 19 issue
  114 |     expect(newestBox!.y).toBeLessThan(olderBox!.y);
  115 |   });
  116 | });
  117 | 
```