<div align="center">
  <h1>⚡ localrepo — Git & GitHub Complete Developer Guide</h1>
  <p><b>Daily workflow essentials se lekar industrial team collaboration tak ka complete roadmap.</b></p>
  <p><code>localrepo</code> Git workflows, privacy identity setup aur production-ready concepts ka structured collection hai.</p>
</div>

<hr />

<h2>📂 Repository Architecture</h2>

<p>Is repository ko do dedicated modules me divide kiya gaya hai taaki zaroorat ke hisaab se sahi document refer kiya ja sake:</p>

<table width="100%">
  <thead>
    <tr>
      <th align="left">File Name</th>
      <th align="left">Level</th>
      <th align="left">Covered Content</th>
      <th align="left">Best For</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b><a href="./Notes.md">Notes.md</a></b></td>
      <td><code>Daily Essentials</code></td>
      <td>
        <ul>
          <li>Global Identity (Anonymous noreply emails)</li>
          <li>Practice Repos ke liye Local Identity Override</li>
          <li>Project Init, Push, Clone &amp; Pull Workflows</li>
          <li>Branching, Merging &amp; Stashing</li>
        </ul>
      </td>
      <td>Daily development, personal projects aur quick CLI reference.</td>
    </tr>
    <tr>
      <td><b><a href="./Advanced-Git.md">Advanced-Git.md</a></b></td>
      <td><code>Production &amp; Team</code></td>
      <td>
        <ul>
          <li>Merge Conflicts resolve karne ka step-by-step tareeqa</li>
          <li>Mistake Recovery (<code>git reset</code>, <code>revert</code>, <code>reflog</code>)</li>
          <li>Linear History with <code>git rebase</code></li>
          <li>Selective Commits with <code>git cherry-pick</code> &amp; PR culture</li>
        </ul>
      </td>
      <td>Enterprise codebases, team projects aur accidental data recovery.</td>
    </tr>
  </tbody>
</table>

<hr />

<h2>🚀 How to Use This Repository</h2>

<ol>
  <li>
    <b>Clone Repository:</b> Kisi naye system par is repo ko clone karne ke liye run karein:
    <pre><code>git clone https://github.com/djgitstor/localrepo.git</code></pre>
  </li>
  <li>
    <b>Naya System Setup:</b> Agar naya machine ya fresh Git install kiya hai, toh sabse pehle <code>Notes.md</code> ke <b>Section 1</b> se global identity config karein.
  </li>
  <li>
    <b>Daily Coding:</b> Day-to-day commands (add, commit, push, branch setup) ke liye <code>Notes.md</code> ko standard reference cheatsheet ki tarah use karein.
  </li>
  <li>
    <b>Team &amp; Edge Cases:</b> Jab merge conflict aaye, production me koi bug revert karna ho, ya branches rebase karni ho, tab <code>Advanced-Git.md</code> follow karein.
  </li>
</ol>

<hr />

<h2>🛡️ Key Architecture Highlights</h2>

<ul>
  <li><b>Privacy-First Commits:</b> Real email expose hone se rokne ke liye GitHub noreply routing standards.</li>
  <li><b>Clean Separation:</b> Global professional identity ke sath folder-level practice identities ko isolate rakhna.</li>
  <li><b>Modern Branch Standard:</b> Har jagah legacy <code>master</code> ke bajaye standard <code>main</code> branch naming convention.</li>
</ul>
