# Pacvue Agent — future design prototype

A clickable concept prototype of an agentic-first Pacvue: one project per brand line, with an agent that works in the background, asks for approval within graduated rules, and keeps charts, tasks, memory and MCP permissions in one place.

**Live demo:** https://zoezheng0.github.io/pacvue-agent-futuredesign/

Concept only. All data is sample data; nothing is connected to a real account.

## What to try

1. On the Projects home, open the **risk line** at the bottom of a card (the small arrow): it lists the important risk messages for that project, and **Follow up** jumps into the project with that risk already quoted in a side chat. Below the cards, **Across all projects** is one agent summary with quick actions.
2. Open *Kitchen Brand Line* (already configured). Tick "Do this automatically from now on" on a suggestion, then look at Settings › MCP and Memory to see the rule and the memory entry it created.
3. **Hover** a channel on the channel bar to pick a platform; the coloured dot says whether the agent acts (green), suggests (amber) or only reads (grey) there. **+ Add channel** brings in Social, Paid search or Agentic; Cross-channel only rolls up what is on the bar.
4. Expand the *Spend & sales* chart and ask why spend stepped up on Oct 20; the chart redraws to answer.
5. Type a task into the bottom bar and watch it plan, preview and execute.
6. **Select any text** on the page (an insight line, a KPI, a table cell, a log line) and choose **Start a side chat**: a panel opens with the selection quoted; ask about it, open the chart behind it, pin the answer or turn it into a task. Several side chats can be open as tabs. The sessions column collapses in place (the icon next to "Sessions" brings it back) and the insight rail folds on narrower screens.
7. Press **⌘K** (or the search icon) to jump to any campaign, session, task, file or setting; ⇧↵ sends the typed text to the agent instead. ⌘J focuses the ask bar.
8. The avatar in the top right opens the account menu: dark mode (also follows the system), language, role & user management, sign out.

## Design principles behind it

Intent over interface · three layers (ambient, directed, on demand) · trust as a first-class artifact · graduated control captured at approval time · guardrails separate from permissions · capability honesty per channel · work compounds (sessions → skills → automations) · design for agents as users · the subtraction test.

*Holiday Gifting 2026* opens empty on purpose so you can walk through the 3-step onboarding.

Single file, no build step: open `index.html` in any browser.
