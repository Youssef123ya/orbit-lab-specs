# Orbit Lab publication kit

Prepared locally on 2026-10-30. The repository was created and the demo was published at the participant's request. No Devpost entry has been sent.

## Repository

Public repository: https://github.com/Youssef123ya/orbit-lab-specs

Public video: https://www.youtube.com/watch?v=7s5lA8JthsY

Description: A spatial eclipse lesson for SPECS, built with Codex and CLAD in
Lens Studio, with procedural graphics, UIKit controls and LEAF integration tests.

Include the project manifest, Assets, Packages, Plugins, README, shared notices
and devpost planning documents. Keep `.gitignore` and `.gitattributes`.
The public repository stores binary assets directly in Git. Do not upload the entire working directory
through a browser: ignored keys, personal answers and generated state must stay
local. The captioned video is published separately on YouTube.

Available routes:

- GitHub CLI: create the repository, then push using Git.
- GitHub connector: use it for supported repository operations.
- GitHub website: create the repository, then use plain Git to push.

The current GitHub connector has no repository-creation tool, and `gh` was not
found on PATH during preparation. Website creation plus Git is an available
fallback once publication is requested. Codex can help with the chosen route.

## YouTube

Title: Orbit Lab — Learn Why Eclipses Happen | SPECS AR Demo

File: `Assets/Build/QA/orbit-lab-demo.mp4`

Duration: 121.198 seconds (2:01). H.264 video and AAC audio. Explanatory captions
are burned in; editable SRT and ASS captions remain beside the video. There is
no spoken narration. Sampled frames and full decode were checked successfully.

Description draft:

> Why doesn't every new moon cause an eclipse? Orbit Lab is a spatial learning
> experience for SPECS. Move the Moon, follow its shadow and solve three short
> challenges about solar eclipses, lunar eclipses and orbital tilt.
>
> This video shows the working Lens in Lens Studio Interactive Preview using
> simulated pinch input. It covers a wrong answer, both eclipse alignments,
> the tilted orbit, completion and Replay.
>
> Built with Codex, CLAD and Lens Studio MCP. The offline lesson uses procedural
> MeshBuilder graphics and SIK/UIKit controls. Five LEAF scenarios passed.
> Proportions and tilt are exaggerated teaching aids. Real glasses comfort,
> tracking and performance have not been tested.
>
> Built for Learn AR with SPECS.
>
> Project repository: REPLACE_WITH_PUBLIC_REPOSITORY_URL

Optional thumbnail: `Assets/Build/QA/solar.jpg`.

Use Public visibility for the final event demo. Replace the repository
placeholder before publishing the description. The participant must answer
any channel-specific audience or account questions themselves where required.

## Public-file audit

The pre-publication check examined Git's candidate file list, honoring ignore
rules: 1,111 files totaling 21,688,721 bytes; 1,021 UTF-8 text files scanned.
No matches were found for private-key headers, common GitHub/OpenAI/AWS/Google/
Slack credential formats, or Windows user-directory paths. The largest candidate
file was the generated music WAV (6,889,208 bytes).

The ignored signing key, private Devpost state, LEAF plugin settings and MP4
files were checked as excluded. The origin remote now points to the public repository. This targeted scan is
not a guarantee about every credential format or binary package; repeat the
final readiness scan after the publication file set changes.

## Participant reflection prompts

The personal form answers already saved locally must be reused privately.
The participant delegated the remaining reflection drafts. Assistant-selected personal ratings are marked as assumptions for the final entry review.
Do not copy personal responses into this public document.

Useful factual build record for answering the troubleshooting question:

- The original imported SIK artifact compiled but failed at startup with a
  component/decorator error; supported unpack restored source execution.
- Inspection examples expected different package namespaces; their example
  imports were repaired for this project.
- Preview interaction helper versions needed compatibility changes through the
  Asset Library. The participant handled native package permission prompts.
- Captures exposed a clipped control card; its placement was adjusted, followed
  by a passing full-flow integration run.

These describe observed engineering events. They do not claim how the
participant felt, which step they found hardest, or what they learned.

## Next review

Record the public repository and YouTube watch URLs in the submission draft.
Verify the links without relying on a signed-in session, reuse saved personal
answers, collect the missing reflections, and run the final submission workflow.
Final entry requires its explicit confirmation after the concrete review.
