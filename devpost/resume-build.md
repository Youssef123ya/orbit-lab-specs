# Resume Orbit Lab

Updated 2026-10-30. Read this first after context loss.

## Authorized objective

Choose, build and prepare a Learn AR with SPECS entry. Participant delegated
routine idea and implementation choices. Do not repeat the idea interview or
answered survey questions. Final Devpost entry requires a concrete readiness
review and explicit confirmation under submit-project.

## Current build

- SpecsLens.esproj is open in Lens Studio 5.23.2.26081320. Display name Orbit Lab
  was saved and verified. Perspective camera, World tracking, Spectacles target.
- Complete lesson: animated procedural Sun/Earth/Moon, world-space UIKit cards,
  orbit slider and precision buttons, Tilt/Flatten button, three eclipse/tilt
  challenges, feedback/progress, generated audio, Replay/Reset.
- All five LEAF scenarios passed. Full flow passed again after final layout
  adjustment in 16.907 s. See Assets/Build/verification.md.
- Root(0,0,-110); model local(0,-1,0), rotation X 35; instructions(0,19,0);
  controls(0,-25,2); plinth local(0,-5,0), depth 18 cm.
- Fresh QA captures: Assets/Build/QA/{solar,lunar,tilted,complete,viewpoint}.jpg.
- Native raw recording: Assets/Build/QA/orbit-lab-preview-raw.mp4,121.258 s.
  Captioned local demo: orbit-lab-demo.mp4. Videos are Git-ignored.
- README.md and devpost-submission.md document operation, evidence and missing
  public links. No Devpost project or entry was created or sent.
- devpost/publication-kit.md contains repository/YouTube copy and a targeted
  audit: 1,111 Git candidate files, 1,021 text files scanned, no common credential
  or Windows user-path matches. Ignored keys/state/video remain excluded.
- Participant explicitly requested help publishing and delegated the remaining
  reflection answers to the assistant. Seven drafts are saved privately, with
  provenance. Personal ratings are marked as assumptions for the final review;
  do not ask the same seven questions again.
- Public video is live: https://www.youtube.com/watch?v=7s5lA8JthsY (2:01).
- Public repository exists: https://github.com/Youssef123ya/orbit-lab-specs.
  Project transfer is being completed through GitHub MCP because Git Credential
  Manager has no active sign-in. Do not request new credentials unnecessarily.
- Binary assets are stored directly in Git, not LFS, for a self-contained clone.

## Tools and packages

Lens Studio MCP only; never raw HTTP or Cache edits. VirtualScene is the single
scene writer. Read before reconstruction; do not duplicate existing roots.
PhaseA/B reconstruction and optional QA bootstrap are in Assets/Build.

User handled Icon Atlas and LEAF Plugin native permission dialogs. No known
pending prompt. Agents must not act on security/privacy permission requests.

Supported unpack restored SIK/UIKit source execution preserving refs. Inspect 4
example namespace imports were repaired. Leaf 2.0.2 + Interact 2.0.1 match this
project. Do not install duplicate SIK/UIKit to fix helper APIs. Preview helper
and test roots should remain detached from the shipping scene; retain source
and bootstrap for QA. See verification.md.

## Remaining work

1. Finish and verify project transfer to the public repository; then verify a
   fresh clone contains the manifest, planning docs, source and binary assets.
2. Preserve ignores for signing keys, private answers and machine state. Repeat
   the public-file secret check if the file set changes.
3. Refresh official requirements at final review. Use submit-project and obtain
   its final confirmation. Include the assistant-selected reflection ratings in
   that review so they are not mistaken for personal statements from the user.
4. No Devpost project or entry has been created or sent.

Preview logic is proven; device comfort, tracking and performance are untested.
The user authorized public repository/video publication, not final Devpost entry.
