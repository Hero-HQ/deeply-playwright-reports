# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: pr-408-sort-dropdown-ux.spec.ts >> PR-408 Sort — Dropdown UX, Accessibility & ARIA >> D.2 Clicking outside the dropdown closes it and preserves the current sort
- Location: tests/pr-408-sort-dropdown-ux.spec.ts:36:7

# Error details

```
Error: locator.click: Error: strict mode violation: locator('div.fixed.inset-0') resolved to 2 elements:
    1) <div aria-hidden="true" class="fixed inset-0 bg-deep/30 z-40 md:hidden transition-opacity duration-300 opacity-0 pointer-events-none"></div> aka locator('div').nth(1)
    2) <div class="fixed inset-0 z-10"></div> aka locator('.fixed.inset-0.z-10')

Call log:
  - waiting for locator('div.fixed.inset-0')

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
                - generic [ref=e255]: Date created
                - img [ref=e256]
              - generic [ref=e259]:
                - button "Urgency" [ref=e260] [cursor=pointer]
                - button "Importance" [ref=e261] [cursor=pointer]
                - button "Date created" [ref=e262] [cursor=pointer]:
                  - text: Date created
                  - img [ref=e263]
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
                - paragraph [ref=e293]: Fresh Issue No Nudge Test
                - generic [ref=e294]: Haven’t touched this in 5 days
                - generic [ref=e295]:
                  - generic [ref=e296]: Apr 24
                  - button "Work through this" [ref=e297]
              - generic [ref=e298] [cursor=pointer]:
                - generic [ref=e300]:
                  - generic [ref=e301]: 🔒
                  - text: Private
                - paragraph [ref=e302]: Staleness Nudge Test Issue - Kanban
                - generic [ref=e303]: Haven’t touched this in 17 days
                - generic [ref=e304]:
                  - generic [ref=e305]: Apr 24
                  - button "Work through this" [ref=e306]
              - generic [ref=e307] [cursor=pointer]:
                - generic [ref=e309]:
                  - generic [ref=e310]: 🔒
                  - text: Private
                - paragraph [ref=e311]: Fresh Proof Issue — just started
                - generic [ref=e312]:
                  - generic [ref=e313]: Apr 24
                  - button "Work through this" [ref=e314]
              - generic [ref=e315] [cursor=pointer]:
                - generic [ref=e317]:
                  - generic [ref=e318]: 🔒
                  - text: Private
                - paragraph [ref=e319]: QA Fresh Issue - No Staleness Nudge
                - generic [ref=e320]:
                  - generic [ref=e321]: Apr 24
                  - button "Work through this" [ref=e322]
              - generic [ref=e323] [cursor=pointer]:
                - generic [ref=e325]:
                  - generic [ref=e326]: 🔒
                  - text: Private
                - paragraph [ref=e327]: QA Fresh Issue - No Staleness Nudge
                - generic [ref=e328]:
                  - generic [ref=e329]: Apr 24
                  - button "Work through this" [ref=e330]
              - generic [ref=e331] [cursor=pointer]:
                - generic [ref=e333]:
                  - img [ref=e334]
                  - text: Shared
                - paragraph [ref=e337]: Future Goals — Joint (Viewer)
                - generic [ref=e338]:
                  - generic [ref=e339]: Apr 22
                  - button "Work through this" [ref=e340]
              - generic [ref=e341] [cursor=pointer]:
                - generic [ref=e343]:
                  - img [ref=e344]
                  - text: Shared
                - paragraph [ref=e347]: Conflict Resolution — Joint (Editor)
                - paragraph [ref=e348]: "# Summary You've identified a conflict that needs resolving between both of you, and the next step is to add some details about what's happening so you can work through it together with clarity and care."
                - generic [ref=e349]:
                  - generic [ref=e350]: Apr 22
                  - button "Work through this" [ref=e351]
              - generic [ref=e352] [cursor=pointer]:
                - generic [ref=e354]:
                  - img [ref=e355]
                  - text: Shared
                - paragraph [ref=e358]: Decision Making — Shared (Editor)
                - paragraph [ref=e359]: It sounds like you've identified that decision-making feels shared when you'd prefer clearer roles—the next step is to jot down a specific example of a decision that felt unclear, so you can explore together what "owned" decision-making would look like for you both.
                - generic [ref=e360]:
                  - generic [ref=e361]: Apr 22
                  - button "Work through this" [ref=e362]
              - generic [ref=e363] [cursor=pointer]:
                - generic [ref=e365]:
                  - img [ref=e366]
                  - text: Shared
                - paragraph [ref=e369]: Trust & Openness — Shared (Viewer)
                - paragraph [ref=e370]: "# Summary You've identified trust and openness as something you'd like to work on together, and the next step is to have a gentle conversation where you both share what's on your minds—maybe starting with what \"trust and openness\" means to each of you and where you're feeling a gap."
                - generic [ref=e371]:
                  - generic [ref=e372]: Apr 22
                  - button "Work through this" [ref=e373]
              - generic [ref=e374] [cursor=pointer]:
                - generic [ref=e376]:
                  - generic [ref=e377]: 🔒
                  - text: Private
                - paragraph [ref=e378]: Communication Pattern — Private
                - paragraph [ref=e379]: It sounds like you've identified that communication patterns might be affecting your relationship, and the next step would be to jot down some specific examples of what's been happening so you can clarify what you'd like to improve together.
                - generic [ref=e380]:
                  - generic [ref=e381]: Apr 22
                  - button "Work through this" [ref=e382]
              - generic [ref=e383] [cursor=pointer]:
                - generic [ref=e385]:
                  - img [ref=e386]
                  - text: Shared
                - paragraph [ref=e389]: Joint Issue - Viewer
                - generic [ref=e390]:
                  - generic [ref=e391]: Apr 22
                  - button "Work through this" [ref=e392]
              - generic [ref=e393] [cursor=pointer]:
                - generic [ref=e395]:
                  - img [ref=e396]
                  - text: Shared
                - paragraph [ref=e399]: Joint Issue - Editor
                - paragraph [ref=e400]: "# Summary You and your partner have identified a concern about your editor, but haven't yet discussed the specifics together—a conversation to align on what's bothering you both would be a caring and practical first step."
                - generic [ref=e401]:
                  - generic [ref=e402]: Apr 22
                  - button "Work through this" [ref=e403]
              - generic [ref=e404] [cursor=pointer]:
                - generic [ref=e406]:
                  - img [ref=e407]
                  - text: Shared
                - paragraph [ref=e410]: Shared - Editor Role
                - paragraph [ref=e411]: "# Summary You've identified a concern about shared editor access, but we need more details about what's happening—let's start by understanding whether this is about permissions not working as expected, unclear role boundaries, or something else entirely, so we can help you resolve it together."
                - generic [ref=e412]:
                  - generic [ref=e413]: Apr 22
                  - button "Work through this" [ref=e414]
              - generic [ref=e415] [cursor=pointer]:
                - generic [ref=e417]:
                  - img [ref=e418]
                  - text: Shared
                - paragraph [ref=e421]: Shared - Viewer Role
                - paragraph [ref=e422]: It sounds like you're working through a permissions question about shared viewing access, and the next step would be to add some details about what you're trying to accomplish so we can help you find the best solution together.
                - generic [ref=e423]:
                  - generic [ref=e424]: Apr 22
                  - button "Work through this" [ref=e425]
              - generic [ref=e426] [cursor=pointer]:
                - generic [ref=e428]:
                  - generic [ref=e429]: 🔒
                  - text: Private
                - paragraph [ref=e430]: Private Test Issue - Lifecycle
                - paragraph [ref=e431]: "# Summary You've just created this issue to test the lifecycle process, and the next step is to add details about what you'd like to track so we can move forward together!"
                - generic [ref=e432]:
                  - generic [ref=e433]: Apr 22
                  - button "Work through this" [ref=e434]
              - generic [ref=e435] [cursor=pointer]:
                - generic [ref=e436]:
                  - generic [ref=e437]: Communication
                  - generic [ref=e438]:
                    - img [ref=e439]
                    - text: Shared
                - paragraph [ref=e442]: We keep having the same argument
                - generic [ref=e443]:
                  - generic [ref=e444]: Apr 22
                  - button "Work through this" [ref=e445]
              - generic [ref=e446] [cursor=pointer]:
                - generic [ref=e448]:
                  - generic [ref=e449]: 🔒
                  - text: Private
                - paragraph [ref=e450]: Stale Proof Issue — 5 days untouched
                - generic [ref=e451]: Haven’t touched this in 8 days
                - generic [ref=e452]:
                  - generic [ref=e453]: Apr 19
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
                - paragraph [ref=e466]: Staleness Nudge Test Issue - Resolving
                - generic [ref=e467]: Haven’t touched this in 17 days
                - generic [ref=e468]:
                  - generic [ref=e469]: Updated Apr 10
                  - button "Continue" [ref=e470]
              - generic [ref=e471] [cursor=pointer]:
                - generic [ref=e473]:
                  - generic [ref=e474]: 🔒
                  - text: Private
                - paragraph [ref=e475]: QA Stale Issue - Staleness Nudge Test
                - generic [ref=e476]:
                  - generic [ref=e477]: Updated Apr 24
                  - button "Continue" [ref=e478]
              - generic [ref=e479] [cursor=pointer]:
                - generic [ref=e481]:
                  - generic [ref=e482]: 🔒
                  - text: Private
                - paragraph [ref=e483]: QA Stale Issue - Staleness Nudge Test
                - generic [ref=e484]:
                  - generic [ref=e485]: Updated Apr 24
                  - button "Continue" [ref=e486]
              - generic [ref=e487] [cursor=pointer]:
                - generic [ref=e489]:
                  - generic [ref=e490]: 🔒
                  - text: Private
                - paragraph [ref=e491]: QA Nav Fix Test Issue
                - paragraph [ref=e492]: "# Summary This QA navigation fix is ready for you to add details that describe what needs testing — once you fill those in, the team can start working on it."
                - generic [ref=e493]:
                  - generic [ref=e494]: Updated Apr 24
                  - button "Continue" [ref=e495]
              - generic [ref=e496] [cursor=pointer]:
                - generic [ref=e498]:
                  - img [ref=e499]
                  - text: Shared
                - paragraph [ref=e502]: QA Partner Role Test Issue (Shared/Resolving)
                - paragraph [ref=e503]: "# Summary It sounds like you're exploring a QA partner role and are just getting started—next, it would help to add some details about what you're testing or what specific partnership dynamic you'd like feedback on."
                - generic [ref=e504]:
                  - generic [ref=e505]: Updated Apr 24
                  - button "Continue" [ref=e506]
              - generic [ref=e507] [cursor=pointer]:
                - generic [ref=e509]:
                  - img [ref=e510]
                  - text: Shared
                - paragraph [ref=e513]: QA Scope Removal Test Issue
                - paragraph [ref=e514]: "# Summary It looks like this issue needs some love—there are no details yet, so the next step is to add specifics about what QA scope is being removed and why, which will help clarify the path forward."
                - generic [ref=e515]:
                  - generic [ref=e516]: Updated Apr 24
                  - button "Continue" [ref=e517]
              - generic [ref=e518] [cursor=pointer]:
                - generic [ref=e520]:
                  - generic [ref=e521]: 🔒
                  - text: Private
                - paragraph [ref=e522]: QA Hydration Test Issue
                - generic [ref=e523]:
                  - generic [ref=e524]: Updated Apr 24
                  - button "Continue" [ref=e525]
          - generic [ref=e526]:
            - generic [ref=e528]:
              - generic [ref=e530]: Resolved
              - generic [ref=e531]: "2"
            - generic [ref=e532]:
              - generic [ref=e533] [cursor=pointer]:
                - generic [ref=e535]:
                  - generic [ref=e536]: 🔒
                  - text: Private
                - paragraph [ref=e537]: Resolved Issue No Nudge Test
                - generic [ref=e538]:
                  - generic [ref=e539]: Resolved Apr 10
                  - button "View" [ref=e540]
              - generic [ref=e541] [cursor=pointer]:
                - generic [ref=e543]:
                  - img [ref=e544]
                  - text: Shared
                - paragraph [ref=e547]: QA Partner Role Test Issue (Shared/Resolved)
                - generic [ref=e548]:
                  - generic [ref=e549]: Resolved Apr 23
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
  3   | test.describe("PR-408 Sort — Dropdown UX, Accessibility & ARIA", () => {
  4   |   test.beforeEach(async ({ page }) => {
  5   |     await page.goto("/issues");
  6   |     await page.evaluate(() => localStorage.clear());
  7   |     await page.reload();
  8   |     await expect(page.getByRole("button", { name: "Sort issues" })).toBeVisible();
  9   |   });
  10  | 
  11  |   // D.1 — Default sort is 'Date created' for a fresh session
  12  |   test("D.1 Default sort is Date created for a fresh session (empty localStorage)", async ({ page }) => {
  13  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  14  | 
  15  |     // Label shows Date created by default
  16  |     await expect(sortBtn).toContainText("Date created");
  17  | 
  18  |     // Open dropdown and verify Date created has checkmark, others do not
  19  |     await sortBtn.click();
  20  | 
  21  |     const dateCreatedOption = page.getByRole("button", { name: "Date created" }).last();
  22  |     await expect(dateCreatedOption.locator("img, svg")).toBeVisible();
  23  | 
  24  |     await expect(
  25  |       page.getByRole("button", { name: "Urgency" }).locator("img, svg")
  26  |     ).not.toBeAttached();
  27  |     await expect(
  28  |       page.getByRole("button", { name: "Importance" }).locator("img, svg")
  29  |     ).not.toBeAttached();
  30  | 
  31  |     // Close dropdown
  32  |     await page.keyboard.press("Escape");
  33  |   });
  34  | 
  35  |   // D.2 — Clicking outside the dropdown closes it without changing sort
  36  |   test("D.2 Clicking outside the dropdown closes it and preserves the current sort", async ({ page }) => {
  37  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  38  | 
  39  |     // Open dropdown
  40  |     await sortBtn.click();
  41  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "true");
  42  | 
  43  |     // Click the fixed inset overlay to trigger click-outside close
> 44  |     await page.locator("div.fixed.inset-0").click();
      |                                             ^ Error: locator.click: Error: strict mode violation: locator('div.fixed.inset-0') resolved to 2 elements:
  45  | 
  46  |     // Dropdown should close
  47  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  48  |     await expect(page.getByRole("button", { name: "Urgency" })).not.toBeVisible();
  49  | 
  50  |     // Label unchanged — still Date created
  51  |     await expect(sortBtn).toContainText("Date created");
  52  |   });
  53  | 
  54  |   // D.2 continued — clicking outside when Urgency is active preserves Urgency
  55  |   test("D.2 Clicking outside preserves previously selected sort (Urgency)", async ({ page }) => {
  56  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  57  | 
  58  |     // Set sort to Urgency first
  59  |     await sortBtn.click();
  60  |     await page.getByRole("button", { name: "Urgency" }).click();
  61  |     await expect(sortBtn).toContainText("Urgency");
  62  | 
  63  |     // Re-open dropdown
  64  |     await sortBtn.click();
  65  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "true");
  66  | 
  67  |     // Click the fixed inset overlay to trigger click-outside close
  68  |     await page.locator("div.fixed.inset-0").click();
  69  | 
  70  |     // Dropdown closes, sort still Urgency
  71  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  72  |     await expect(sortBtn).toContainText("Urgency");
  73  |   });
  74  | 
  75  |   // D.3 — Chevron rotates 180° when dropdown opens and back when closed
  76  |   test("D.3 Chevron SVG rotates 180° on open and reverts on close", async ({ page }) => {
  77  |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  78  | 
  79  |     // Before open: chevron should not have rotate(180deg)
  80  |     // The chevron is the last img/svg inside the sort button
  81  |     const chevron = sortBtn.locator("img, svg").last();
  82  | 
  83  |     const closedTransform = await chevron.evaluate((el) => {
  84  |       return (el as HTMLElement).style.transform;
  85  |     });
  86  |     // Closed state: no transform or empty string
  87  |     expect(closedTransform === "" || closedTransform === "none" || closedTransform === undefined).toBeTruthy();
  88  | 
  89  |     // Open dropdown
  90  |     await sortBtn.click();
  91  |     await expect(sortBtn).toHaveAttribute("aria-expanded", "true");
  92  | 
  93  |     const openTransform = await chevron.evaluate((el) => {
  94  |       return (el as HTMLElement).style.transform;
  95  |     });
  96  |     expect(openTransform).toBe("rotate(180deg)");
  97  | 
  98  |     // Close by selecting an option
  99  |     await page.getByRole("button", { name: "Urgency" }).click();
  100 |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  101 | 
  102 |     const closedAgainTransform = await chevron.evaluate((el) => {
  103 |       return (el as HTMLElement).style.transform;
  104 |     });
  105 |     expect(closedAgainTransform === "" || closedAgainTransform === "none" || closedAgainTransform === undefined).toBeTruthy();
  106 |   });
  107 | 
  108 |   // H.1 — Accessibility: aria-label and aria-expanded
  109 |   test("H.1 Sort button has correct aria-label='Sort issues' and aria-expanded tracks open state", async ({ page }) => {
  110 |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  111 | 
  112 |     // Closed state
  113 |     await expect(sortBtn).toHaveAttribute("aria-label", "Sort issues");
  114 |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  115 | 
  116 |     // Open dropdown
  117 |     await sortBtn.click();
  118 |     await expect(sortBtn).toHaveAttribute("aria-expanded", "true");
  119 | 
  120 |     // Select an option to close
  121 |     await page.getByRole("button", { name: "Urgency" }).click();
  122 |     await expect(sortBtn).toHaveAttribute("aria-expanded", "false");
  123 |   });
  124 | 
  125 |   // H.1 continued — all three dropdown option buttons are accessible by role
  126 |   test("H.1 All sort option buttons are accessible by role and name when dropdown is open", async ({ page }) => {
  127 |     const sortBtn = page.getByRole("button", { name: "Sort issues" });
  128 |     await sortBtn.click();
  129 | 
  130 |     // All three options accessible by getByRole
  131 |     await expect(page.getByRole("button", { name: "Urgency" })).toBeVisible();
  132 |     await expect(page.getByRole("button", { name: "Importance" })).toBeVisible();
  133 |     await expect(page.getByRole("button", { name: "Date created" }).last()).toBeVisible();
  134 |   });
  135 | });
  136 | 
```