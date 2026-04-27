# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: pr-408-sort-happy-path.spec.ts >> PR-408 Sort — Happy Path & Date Created correctness >> A.2 Checkmark moves to newly selected sort option in re-opened dropdown
- Location: tests/pr-408-sort-happy-path.spec.ts:70:7

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: getByRole('button', { name: 'Importance' }).locator('img')
Expected: visible
Timeout: 5000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 5000ms
  - waiting for getByRole('button', { name: 'Importance' }).locator('img')

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e2]:
    - complementary [ref=e3]:
      - generic [ref=e5]:
        - button "Collapse sidebar" [ref=e6] [cursor=pointer]:
          - img [ref=e7]
        - link "Deeply" [ref=e10] [cursor=pointer]:
          - /url: /dashboard
          - img [ref=e11]
          - generic [ref=e13]: Deeply
      - navigation [ref=e14]:
        - button "Home" [ref=e15] [cursor=pointer]:
          - img [ref=e17]
          - generic [ref=e20]: Home
        - button "Issues" [ref=e21] [cursor=pointer]:
          - img [ref=e23]
          - generic [ref=e26]: Issues
        - button "Commitments" [ref=e27] [cursor=pointer]:
          - img [ref=e29]
          - generic [ref=e32]: Commitments
        - button "Chat" [ref=e33] [cursor=pointer]:
          - img [ref=e35]
          - generic [ref=e37]: Chat
        - button "Reminders" [ref=e38] [cursor=pointer]:
          - img [ref=e40]
          - generic [ref=e43]: Reminders
        - button "Profile" [ref=e44] [cursor=pointer]:
          - img [ref=e46]
          - generic [ref=e49]: Profile
        - generic [ref=e50]:
          - generic [ref=e51]: Recents
          - generic [ref=e52]:
            - button "Untitled" [ref=e53] [cursor=pointer]:
              - generic "Untitled" [ref=e54]
            - button "Conversation options" [ref=e55] [cursor=pointer]:
              - img [ref=e56]
          - generic [ref=e60]:
            - button "Untitled" [ref=e61] [cursor=pointer]:
              - generic "Untitled" [ref=e62]
            - button "Conversation options" [ref=e63] [cursor=pointer]:
              - img [ref=e64]
          - generic [ref=e68]:
            - button "Untitled" [ref=e69] [cursor=pointer]:
              - generic "Untitled" [ref=e70]
            - button "Conversation options" [ref=e71] [cursor=pointer]:
              - img [ref=e72]
          - generic [ref=e76]:
            - button "Untitled" [ref=e77] [cursor=pointer]:
              - generic "Untitled" [ref=e78]
            - button "Conversation options" [ref=e79] [cursor=pointer]:
              - img [ref=e80]
          - generic [ref=e84]:
            - button "Untitled" [ref=e85] [cursor=pointer]:
              - generic "Untitled" [ref=e86]
            - button "Conversation options" [ref=e87] [cursor=pointer]:
              - img [ref=e88]
          - generic [ref=e92]:
            - button "Untitled" [ref=e93] [cursor=pointer]:
              - generic "Untitled" [ref=e94]
            - button "Conversation options" [ref=e95] [cursor=pointer]:
              - img [ref=e96]
          - generic [ref=e100]:
            - button "Untitled" [ref=e101] [cursor=pointer]:
              - generic "Untitled" [ref=e102]
            - button "Conversation options" [ref=e103] [cursor=pointer]:
              - img [ref=e104]
          - generic [ref=e108]:
            - button "Untitled" [ref=e109] [cursor=pointer]:
              - generic "Untitled" [ref=e110]
            - button "Conversation options" [ref=e111] [cursor=pointer]:
              - img [ref=e112]
          - generic [ref=e116]:
            - button "Untitled" [ref=e117] [cursor=pointer]:
              - generic "Untitled" [ref=e118]
            - button "Conversation options" [ref=e119] [cursor=pointer]:
              - img [ref=e120]
          - generic [ref=e124]:
            - button "Untitled" [ref=e125] [cursor=pointer]:
              - generic "Untitled" [ref=e126]
            - button "Conversation options" [ref=e127] [cursor=pointer]:
              - img [ref=e128]
          - generic [ref=e132]:
            - button "Untitled" [ref=e133] [cursor=pointer]:
              - generic "Untitled" [ref=e134]
            - button "Conversation options" [ref=e135] [cursor=pointer]:
              - img [ref=e136]
          - generic [ref=e140]:
            - button "Untitled" [ref=e141] [cursor=pointer]:
              - generic "Untitled" [ref=e142]
            - button "Conversation options" [ref=e143] [cursor=pointer]:
              - img [ref=e144]
          - generic [ref=e148]:
            - button "Untitled" [ref=e149] [cursor=pointer]:
              - generic "Untitled" [ref=e150]
            - button "Conversation options" [ref=e151] [cursor=pointer]:
              - img [ref=e152]
          - generic [ref=e156]:
            - button "Untitled" [ref=e157] [cursor=pointer]:
              - generic "Untitled" [ref=e158]
            - button "Conversation options" [ref=e159] [cursor=pointer]:
              - img [ref=e160]
          - generic [ref=e164]:
            - button "Decision-making friction in …" [ref=e165] [cursor=pointer]:
              - generic "Decision-making friction in our relationship" [ref=e166]: Decision-making friction in …
            - button "Conversation options" [ref=e167] [cursor=pointer]:
              - img [ref=e168]
          - generic [ref=e172]:
            - button "Untitled" [ref=e173] [cursor=pointer]:
              - generic "Untitled" [ref=e174]
            - button "Conversation options" [ref=e175] [cursor=pointer]:
              - img [ref=e176]
          - generic [ref=e180]:
            - button "Untitled" [ref=e181] [cursor=pointer]:
              - generic "Untitled" [ref=e182]
            - button "Conversation options" [ref=e183] [cursor=pointer]:
              - img [ref=e184]
          - generic [ref=e188]:
            - button "Untitled" [ref=e189] [cursor=pointer]:
              - generic "Untitled" [ref=e190]
            - button "Conversation options" [ref=e191] [cursor=pointer]:
              - img [ref=e192]
          - generic [ref=e196]:
            - button "Untitled" [ref=e197] [cursor=pointer]:
              - generic "Untitled" [ref=e198]
            - button "Conversation options" [ref=e199] [cursor=pointer]:
              - img [ref=e200]
          - generic [ref=e204]:
            - button "How we make decisions togeth…" [ref=e205] [cursor=pointer]:
              - generic "How we make decisions together" [ref=e206]: How we make decisions togeth…
            - button "Conversation options" [ref=e207] [cursor=pointer]:
              - img [ref=e208]
          - generic [ref=e212]:
            - button "Decision-making friction in …" [ref=e213] [cursor=pointer]:
              - generic "Decision-making friction in our relationship" [ref=e214]: Decision-making friction in …
            - button "Conversation options" [ref=e215] [cursor=pointer]:
              - img [ref=e216]
          - generic [ref=e220]:
            - 'button "QA: persistent input test" [ref=e221] [cursor=pointer]':
              - 'generic "QA: persistent input test" [ref=e222]'
            - button "Conversation options" [ref=e223] [cursor=pointer]:
              - img [ref=e224]
          - generic [ref=e228]:
            - button "We keep arguing about the sa…" [ref=e229] [cursor=pointer]:
              - generic "We keep arguing about the same things" [ref=e230]: We keep arguing about the sa…
            - button "Conversation options" [ref=e231] [cursor=pointer]:
              - img [ref=e232]
      - button "Q QA Agent with Partner B" [ref=e237] [cursor=pointer]:
        - generic [ref=e238]: Q
        - generic [ref=e239]:
          - generic [ref=e240]: QA Agent
          - generic [ref=e241]: with Partner B
        - img [ref=e242]
    - main [ref=e245]:
      - generic [ref=e246]:
        - generic [ref=e247]:
          - generic [ref=e248]:
            - generic [ref=e249]:
              - heading "My Issues" [level=1] [ref=e250]
              - link "+ New conversation" [ref=e251] [cursor=pointer]:
                - /url: /chat
            - generic [ref=e252]:
              - button "Sort issues" [expanded] [active] [ref=e253] [cursor=pointer]:
                - img [ref=e254]
                - generic [ref=e255]: Importance
                - img [ref=e256]
              - generic [ref=e259]:
                - button "Urgency" [ref=e260] [cursor=pointer]
                - button "Importance" [ref=e261] [cursor=pointer]:
                  - text: Importance
                  - img [ref=e262]
                - button "Date created" [ref=e264] [cursor=pointer]
          - generic [ref=e265]:
            - button "Board" [ref=e266] [cursor=pointer]
            - button "List" [ref=e267] [cursor=pointer]
            - button "Matrix" [ref=e268] [cursor=pointer]
        - generic [ref=e271]:
          - generic [ref=e272]:
            - generic [ref=e274]:
              - generic [ref=e276]: New
              - generic [ref=e277]: "18"
            - generic [ref=e278]:
              - generic [ref=e279] [cursor=pointer]:
                - generic [ref=e280]:
                  - generic [ref=e281]: Communication
                  - generic [ref=e282]:
                    - generic [ref=e283]: 🔒
                    - text: Private
                - paragraph [ref=e284]: QA Test Issue
                - paragraph [ref=e285]: This issue was created by the QA seed script for automated testing.
                - generic [ref=e286]:
                  - generic [ref=e287]: Apr 27
                  - button "Work through this" [ref=e288]
              - generic [ref=e289] [cursor=pointer]:
                - generic [ref=e291]:
                  - generic [ref=e292]: 🔒
                  - text: Private
                - paragraph [ref=e293]: Communication Pattern — Private
                - paragraph [ref=e294]: It sounds like you've identified that communication patterns might be affecting your relationship, and the next step would be to jot down some specific examples of what's been happening so you can clarify what you'd like to improve together.
                - generic [ref=e295]:
                  - generic [ref=e296]: Apr 22
                  - button "Work through this" [ref=e297]
              - generic [ref=e298] [cursor=pointer]:
                - generic [ref=e299]:
                  - generic [ref=e300]: Communication
                  - generic [ref=e301]:
                    - img [ref=e302]
                    - text: Shared
                - paragraph [ref=e305]: We keep having the same argument
                - generic [ref=e306]:
                  - generic [ref=e307]: Apr 22
                  - button "Work through this" [ref=e308]
              - generic [ref=e309] [cursor=pointer]:
                - generic [ref=e311]:
                  - img [ref=e312]
                  - text: Shared
                - paragraph [ref=e315]: Shared - Editor Role
                - paragraph [ref=e316]: "# Summary You've identified a concern about shared editor access, but we need more details about what's happening—let's start by understanding whether this is about permissions not working as expected, unclear role boundaries, or something else entirely, so we can help you resolve it together."
                - generic [ref=e317]:
                  - generic [ref=e318]: Apr 22
                  - button "Work through this" [ref=e319]
              - generic [ref=e320] [cursor=pointer]:
                - generic [ref=e322]:
                  - img [ref=e323]
                  - text: Shared
                - paragraph [ref=e326]: Joint Issue - Editor
                - paragraph [ref=e327]: "# Summary You and your partner have identified a concern about your editor, but haven't yet discussed the specifics together—a conversation to align on what's bothering you both would be a caring and practical first step."
                - generic [ref=e328]:
                  - generic [ref=e329]: Apr 22
                  - button "Work through this" [ref=e330]
              - generic [ref=e331] [cursor=pointer]:
                - generic [ref=e333]:
                  - img [ref=e334]
                  - text: Shared
                - paragraph [ref=e337]: Shared - Viewer Role
                - paragraph [ref=e338]: It sounds like you're working through a permissions question about shared viewing access, and the next step would be to add some details about what you're trying to accomplish so we can help you find the best solution together.
                - generic [ref=e339]:
                  - generic [ref=e340]: Apr 22
                  - button "Work through this" [ref=e341]
              - generic [ref=e342] [cursor=pointer]:
                - generic [ref=e344]:
                  - img [ref=e345]
                  - text: Shared
                - paragraph [ref=e348]: Joint Issue - Viewer
                - generic [ref=e349]:
                  - generic [ref=e350]: Apr 22
                  - button "Work through this" [ref=e351]
              - generic [ref=e352] [cursor=pointer]:
                - generic [ref=e354]:
                  - img [ref=e355]
                  - text: Shared
                - paragraph [ref=e358]: Future Goals — Joint (Viewer)
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
                  - img [ref=e387]
                  - text: Shared
                - paragraph [ref=e390]: Conflict Resolution — Joint (Editor)
                - paragraph [ref=e391]: "# Summary You've identified a conflict that needs resolving between both of you, and the next step is to add some details about what's happening so you can work through it together with clarity and care."
                - generic [ref=e392]:
                  - generic [ref=e393]: Apr 22
                  - button "Work through this" [ref=e394]
              - generic [ref=e395] [cursor=pointer]:
                - generic [ref=e397]:
                  - generic [ref=e398]: 🔒
                  - text: Private
                - paragraph [ref=e399]: Private Test Issue - Lifecycle
                - paragraph [ref=e400]: "# Summary You've just created this issue to test the lifecycle process, and the next step is to add details about what you'd like to track so we can move forward together!"
                - generic [ref=e401]:
                  - generic [ref=e402]: Apr 22
                  - button "Work through this" [ref=e403]
              - generic [ref=e404] [cursor=pointer]:
                - generic [ref=e406]:
                  - generic [ref=e407]: 🔒
                  - text: Private
                - paragraph [ref=e408]: QA Fresh Issue - No Staleness Nudge
                - generic [ref=e409]:
                  - generic [ref=e410]: Apr 24
                  - button "Work through this" [ref=e411]
              - generic [ref=e412] [cursor=pointer]:
                - generic [ref=e414]:
                  - generic [ref=e415]: 🔒
                  - text: Private
                - paragraph [ref=e416]: QA Fresh Issue - No Staleness Nudge
                - generic [ref=e417]:
                  - generic [ref=e418]: Apr 24
                  - button "Work through this" [ref=e419]
              - generic [ref=e420] [cursor=pointer]:
                - generic [ref=e422]:
                  - generic [ref=e423]: 🔒
                  - text: Private
                - paragraph [ref=e424]: Fresh Proof Issue — just started
                - generic [ref=e425]:
                  - generic [ref=e426]: Apr 24
                  - button "Work through this" [ref=e427]
              - generic [ref=e428] [cursor=pointer]:
                - generic [ref=e430]:
                  - generic [ref=e431]: 🔒
                  - text: Private
                - paragraph [ref=e432]: Fresh Issue No Nudge Test
                - generic [ref=e433]: Haven’t touched this in 5 days
                - generic [ref=e434]:
                  - generic [ref=e435]: Apr 24
                  - button "Work through this" [ref=e436]
              - generic [ref=e437] [cursor=pointer]:
                - generic [ref=e439]:
                  - generic [ref=e440]: 🔒
                  - text: Private
                - paragraph [ref=e441]: Stale Proof Issue — 5 days untouched
                - generic [ref=e442]: Haven’t touched this in 8 days
                - generic [ref=e443]:
                  - generic [ref=e444]: Apr 19
                  - button "Work through this" [ref=e445]
              - generic [ref=e446] [cursor=pointer]:
                - generic [ref=e448]:
                  - generic [ref=e449]: 🔒
                  - text: Private
                - paragraph [ref=e450]: Staleness Nudge Test Issue - Kanban
                - generic [ref=e451]: Haven’t touched this in 17 days
                - generic [ref=e452]:
                  - generic [ref=e453]: Apr 24
                  - button "Work through this" [ref=e454]
          - generic [ref=e455]:
            - generic [ref=e457]:
              - generic [ref=e459]: Working on it
              - generic [ref=e460]: "7"
            - generic [ref=e461]:
              - generic [ref=e462] [cursor=pointer]:
                - generic [ref=e464]:
                  - generic [ref=e465]: 🔒
                  - text: Private
                - paragraph [ref=e466]: QA Hydration Test Issue
                - generic [ref=e467]:
                  - generic [ref=e468]: Updated Apr 24
                  - button "Continue" [ref=e469]
              - generic [ref=e470] [cursor=pointer]:
                - generic [ref=e472]:
                  - img [ref=e473]
                  - text: Shared
                - paragraph [ref=e476]: QA Scope Removal Test Issue
                - paragraph [ref=e477]: "# Summary It looks like this issue needs some love—there are no details yet, so the next step is to add specifics about what QA scope is being removed and why, which will help clarify the path forward."
                - generic [ref=e478]:
                  - generic [ref=e479]: Updated Apr 24
                  - button "Continue" [ref=e480]
              - generic [ref=e481] [cursor=pointer]:
                - generic [ref=e483]:
                  - img [ref=e484]
                  - text: Shared
                - paragraph [ref=e487]: QA Partner Role Test Issue (Shared/Resolving)
                - paragraph [ref=e488]: "# Summary It sounds like you're exploring a QA partner role and are just getting started—next, it would help to add some details about what you're testing or what specific partnership dynamic you'd like feedback on."
                - generic [ref=e489]:
                  - generic [ref=e490]: Updated Apr 24
                  - button "Continue" [ref=e491]
              - generic [ref=e492] [cursor=pointer]:
                - generic [ref=e494]:
                  - generic [ref=e495]: 🔒
                  - text: Private
                - paragraph [ref=e496]: QA Nav Fix Test Issue
                - paragraph [ref=e497]: "# Summary This QA navigation fix is ready for you to add details that describe what needs testing — once you fill those in, the team can start working on it."
                - generic [ref=e498]:
                  - generic [ref=e499]: Updated Apr 24
                  - button "Continue" [ref=e500]
              - generic [ref=e501] [cursor=pointer]:
                - generic [ref=e503]:
                  - generic [ref=e504]: 🔒
                  - text: Private
                - paragraph [ref=e505]: QA Stale Issue - Staleness Nudge Test
                - generic [ref=e506]:
                  - generic [ref=e507]: Updated Apr 24
                  - button "Continue" [ref=e508]
              - generic [ref=e509] [cursor=pointer]:
                - generic [ref=e511]:
                  - generic [ref=e512]: 🔒
                  - text: Private
                - paragraph [ref=e513]: QA Stale Issue - Staleness Nudge Test
                - generic [ref=e514]:
                  - generic [ref=e515]: Updated Apr 24
                  - button "Continue" [ref=e516]
              - generic [ref=e517] [cursor=pointer]:
                - generic [ref=e519]:
                  - generic [ref=e520]: 🔒
                  - text: Private
                - paragraph [ref=e521]: Staleness Nudge Test Issue - Resolving
                - generic [ref=e522]: Haven’t touched this in 17 days
                - generic [ref=e523]:
                  - generic [ref=e524]: Updated Apr 10
                  - button "Continue" [ref=e525]
          - generic [ref=e526]:
            - generic [ref=e528]:
              - generic [ref=e530]: Resolved
              - generic [ref=e531]: "2"
            - generic [ref=e532]:
              - generic [ref=e533] [cursor=pointer]:
                - generic [ref=e535]:
                  - img [ref=e536]
                  - text: Shared
                - paragraph [ref=e539]: QA Partner Role Test Issue (Shared/Resolved)
                - generic [ref=e540]:
                  - generic [ref=e541]: Resolved Apr 23
                  - button "View" [ref=e542]
              - generic [ref=e543] [cursor=pointer]:
                - generic [ref=e545]:
                  - generic [ref=e546]: 🔒
                  - text: Private
                - paragraph [ref=e547]: Resolved Issue No Nudge Test
                - generic [ref=e548]:
                  - generic [ref=e549]: Resolved Apr 10
                  - button "View" [ref=e550]
  - alert [ref=e551]
  - iframe [ref=e552]:
    
  - button "Open Intercom Messenger" [ref=e553] [cursor=pointer]:
    - img [ref=e555]
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
  31  |     await expect(dateCreatedOption.locator("img")).toBeVisible();
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
> 83  |     ).toBeVisible();
      |       ^ Error: expect(locator).toBeVisible() failed
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