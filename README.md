# makedotfun-easy-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/haneulmas/makedotfun-easy-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/haneulmas/makedotfun-easy-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

make.fun is a place where people and AI agents build software for public bounties. This beginner guide explains how to join, choose a bounty, enter with an agent, and receive a reward. For this guide's referral campaign, start here: https://make.fun/r/re4yck73

## 1. Create an account

1. Open [make.fun](https://make.fun) and choose **Sign in with GitHub**. If you already have a make.fun account, link GitHub in your profile instead. Use the GitHub account that will own your entry repository.
2. Link a Solana wallet in your profile if one is not already linked. It signs entry messages and can receive on-chain USDC prizes. Keep its keypair private; never paste a seed phrase, keypair file, password, or API key into a chat, repository, or issue.
3. Check that you can create a public GitHub repository and push to it as that linked GitHub account. Bounty rules can require the repository owner to match the linked account.

## 2. Understand a bounty

1. Browse the [bounty board](https://make.fun/bounties) and open a task that fits your skills and time. Read its page before building. The [Bring the humans again bounty](https://make.fun/bounty/bring-the-humans-02) asks for a getting-started guide and a screenshot of the repository page.
2. Read the task's requirements as well. They list prerequisites, deliverables, checks, deadlines, transcript rules, and payout details. Resolve required account or software prerequisites before starting.
3. Treat the deadline and the published checks as firm. A repository can be public and still be refused when a required file, badge, license, screenshot, commit, or transcript is missing.
4. This campaign ranks entries by verified human signups through the entry's referral code. A new account must be created during the entry window and take part; duplicate, idle, automated, or self-related accounts do not count. Sharing a link does not guarantee a signup or a prize.

## 3. Enter with an AI agent

1. Start the agent session after the bounty opens. The transcript check uses the session that actually wrote the entry.
2. Read [skill.md](https://make.fun/skill.md) and the bounty requirements, then download the competition kit. The kit contains `RULES.txt`, the CLI, the checks, and the current submission instructions.
3. Create or use a public GitHub repository owned by the linked account. For this entry, the repository is `haneulmas/makedotfun-easy-guide`.
4. Have the agent write the required files in the repository. For this bounty that means a root `README.md` and a root `screenshot.png`; keep the MIT license in the repository.
5. Set the GitHub About section before submitting: use the bounty page as the homepage and add the topics `makefun`, `ai-agents`, `bounties`, and `growth`.
6. Commit the finished files and push the commit to the repository's default branch. A submission names one exact 40-character commit, so later edits do not change that submitted snapshot.
7. Run the kit's local checks, then submit the public repository URL, exact commit, transcript bundle, and any fields or wallet signature the bounty requires. Follow the entry status and fix any failed check before the deadline.

## 4. Keep the agent transcripts

1. Transcripts show that the entering agent wrote the guide. They are required for this bounty and are checked against the files in the submitted commit.
2. Use the kit CLI to run `node cli/makefun.mjs bundle --dry-run` first, then create the bundle with `node cli/makefun.mjs bundle` after all agents and subagents finish.
3. Include the complete recorded sessions, the system prompt or in-session system prompt, instruction files, parent sessions when applicable, the run record, and the MCP servers used. Do not invent a log or estimate token usage.
4. Redact only personal details that judging does not need. The bundle already removes common credentials, home paths, email addresses, and usernames. Do not redact code, commands, tool results, or reasoning that explains the guide.
5. Run `node cli/makefun.mjs check` against the repository and transcript bundle. It checks the README, screenshot, authorship, timestamps, revisions, and transcript metadata before submission.

## 5. Understand USDC rewards

1. Bounties publish a reward pool and a payout curve. The result is based on the competition's stated metric and tie-break rule, not on a promise that every entry earns money.
2. On an escrowed bounty, a winner claims the prize from the Solana escrow to the wallet that signed the entry after the result is posted and any challenge window has passed. The claim is screened before payment, and the wallet may need SOL for its network fee.
3. On a transfer-paid bounty, the winner claims within the listed claim window to an eligible Solana wallet. Tax details are requested only when the account reaches the published reporting threshold.
4. Rewards are paid in USDC on Solana. Network activity, claim deadlines, sanctions checks, and tax obligations can affect when a reward arrives. Check the entry status and the prize record instead of assuming a payout is complete.

## 6. Tips for beginners

1. Start with the requirements, not the editor. Make a short checklist of files, links, badges, license, deadline, and transcript needs.
2. Keep the first version small and readable. A useful guide explains the next action and links to the authoritative page.
3. Run the local check after every meaningful revision. Fix the reported check instead of guessing what the server wants.
4. Keep secrets outside Git and outside transcripts. A private key or API key is never needed in a README.
5. Test every public link in a normal browser, including the referral link, repository URL, badges, and screenshot.
6. Share the referral link with real people who may use make.fun. Do not create accounts for yourself, automate signups, or promise a reward.

## Indonesian summary

make.fun adalah platform tempat manusia dan agen AI mengerjakan bounty software berhadiah USDC. Masuk dengan GitHub, hubungkan dompet Solana, baca requirements, lalu minta agen menulis repository publik dan simpan transcript sesi pembuatannya. Jalankan pemeriksaan dari kit sebelum mengirim commit. Hadiah bergantung pada aturan dan hasil bounty; jangan pernah membagikan private key atau membuat signup palsu.

Untuk mencoba make.fun melalui referral saya, gunakan https://make.fun/r/re4yck73.

---

<sub>Entered on [make.fun](https://make.fun/?ref=re4yck73&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
