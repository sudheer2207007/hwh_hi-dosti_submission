HACKWITHHYDERABAD — FINAL SUBMISSION: STEP-BY-STEP GUIDE
------------------------------------------------------

Follow these steps exactly to prepare and submit your final entry.

STEP 1 — Prepare your GitHub repository or Google Drive folder
 - Create a repo (private or public) or a Drive folder named: `hwh_<teamname>_submission`.
 - Within it, create these folders/files:
    - `final_report.pdf` or `final_report.md` (completed report)
    - `presentation.pptx` (5-6 slides)
    - `model/` with your final weights (e.g., best.pt, best.pth)
      - Add a small README: how to load the model & inference command.
    - `results/` with sample detection images, confusion matrix, graphs.
    - `requirements.txt` and `inference_example.sh` or `inference_example.ipynb`.
 - Commit & push all files.

STEP 2 — Add reviewers as collaborators (GitHub only)
 - Go to your repository on GitHub
 - Click **Settings** -> **Manage access** -> **Invite teams or people**
 - Enter these usernames exactly and invite them:
    - Maazsyedm
    - rebekah-bogdanoff
    - epilef68
 - Wait until they accept (if they don't accept, add a note in the Google Form that the repo is viewable via link).

STEP 3 — Verify your mAP50
 - Run your evaluation on the test set exactly as you used for reporting.
 - Record the highest mAP50 value; this is required by the form and will be verified.

STEP 4 — Generate shareable link
 - For GitHub: copy the repository URL (https://github.com/your_org/your_repo)
 - For Google Drive: right-click the folder -> "Get link" -> set to "Anyone with the link can view" -> copy link.

STEP 5 — Fill the Google Form (Final Submission)
 - Open the Final Submission Form: https://docs.google.com/forms/d/e/1FAIpQLSewuxclyjdxEtxBIwpc5MtTQbwqHx-cVMvxDLhsDnnVnOcNOg/viewform?usp=header
 - Enter:
    - Team Name
    - Team Members (full names)
    - Highest mAP50 achieved (numeric value)
    - GitHub Repository/Google Drive Link (paste the link)
    - Answer whether you completed the bonus challenge (Yes/No)
    - Provide any feedback if asked
 - Submit (one submission per team only).

STEP 6 — Confirm & Notify
 - After submission, confirm on Discord (Duality or HackWithHyderabad server) that you submitted.
 - Save the confirmation screenshot/email for your records.

TROUBLESHOOTING & NOTES
 - If your repo is private and reviewers can't access it, ensure they've been added as collaborators.
 - If your model file is too large for GitHub, upload weights to Google Drive and put download instructions or a small script to fetch them.
 - Make sure `requirements.txt` contains specific versions to enable reproducibility (e.g., torch==2.0.1).
 - Double-check the email entered on the form (should be the registered email).

Good luck — submit once and only once. 👍
