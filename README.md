# Task_07_Ethics_Synthetic_Media

## Project Overview

This repository continues directly from my Task 6 synthetic-audio experiment. In Task 6, I used ElevenLabs Text to Speech to generate two versions of the same analytical sports narrative using the same model, voice, and script while changing the Stability and Similarity settings. Both files were explicitly labeled as AI-generated, and the script began with a spoken disclosure.

Task 7 moves from building synthetic media to governing it. Phase A reflects on what the Task 6 experiment made visible about truth, consent, context, scale, disclosure, provenance, detection, platform controls, and professional norms. Phase B turns that reasoning into a concrete synthetic-media policy that a real organization could use.

No new synthetic-media artifact is created for Task 7.

## Task 6 Experience Used as the Foundation

The Task 7 analysis is grounded in the following observations from my Task 6 work:

- Two synthetic-audio attempts were created with ElevenLabs using the same script and generic ElevenLabs voice.
- The second attempt changed Stability and Similarity while keeping the main content and voice constant.
- Both audio files were approximately 116 seconds long.
- The output was clear and polished, but careful listening still revealed synthetic characteristics such as highly controlled cadence, limited breathing, restrained emotional variation, and few conversational imperfections.
- AI Voice Detector classified Attempt 2 as **AI Generated** with a **96% AI score** and classified all **19 analyzed segments** as AI-generated.
- Both original ElevenLabs MP3 exports contained C2PA provenance markers identifying the files as algorithmically generated media.
- After Attempt 2 was re-encoded to a new MP3, the C2PA markers visible in the original file were no longer present in the re-encoded copy.
- No safety refusal occurred during the experiment because the project used a generic synthetic voice and a benign academic script rather than cloning a real person.

These observations made the ethical issues more concrete than they would have been from reading about synthetic media alone.

## Organizational Context

For Phase B, I chose a **University Athletics Communications Office**.

This setting includes communications directors, social-media staff, video and audio producers, student workers, interns, and contractors who create public-facing content about teams, coaches, athletes, events, recruiting, alumni, and institutional announcements. Its audiences can include students, families, alumni, fans, recruits, journalists, donors, and the general public.

I chose this context because it connects naturally to the sports-analysis narrative used in Task 6 and because an athletics communications office has realistic reasons to consider synthetic media: narration, accessibility, prototypes, training, and high-volume content. At the same time, the office works with identifiable people whose voices, reputations, and public statements can carry institutional authority. That makes consent, disclosure, attribution, and review especially important.

## Repository Map

- `PHASE_A_ETHICAL_ANALYSIS.md` — reflection on Task 6, the four required ethical axes, and the mitigation landscape.
- `SYNTHETIC_MEDIA_POLICY.md` — Phase B governance policy for a University Athletics Communications Office.
- `POLICY_LIMITATIONS.md` — stress test of the policy and residual risks.
- `TASK_06_REFERENCE.md` — link/reference back to the separate Task 6 repository.
- `SUBMISSION_CHECKLIST.md` — final GitHub and submission checklist.

## What Surprised Me

The most surprising part of the Task 6 → Task 7 sequence was that the ethical problem appeared even though my own experiment was intentionally low-risk. I used a generic synthetic voice, disclosed that it was synthetic, and did not impersonate a real person. Even so, the experiment showed how easily a written message can be detached from a human speaker and turned into polished, distributable speech.

The provenance experiment was especially important. The original ElevenLabs files carried C2PA information, but the markers I could identify did not survive an ordinary re-encoding test. That made it clear that disclosure and provenance are useful but fragile. A responsible policy therefore cannot rely on a single label, watermark, detector, or metadata field.

The policy in this repository uses layered controls: limits on what may be generated, consent before identity-based synthesis, repeated disclosure, provenance records, human review, incident response, and explicit refusal conditions.

## Task 6 Reference

Task 7 refers back to my Task 6 repository rather than re-uploading the synthetic media.
