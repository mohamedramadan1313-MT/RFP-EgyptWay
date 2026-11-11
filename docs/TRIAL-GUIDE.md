# Your first RFP-EgyptWay review

[Return to the product overview](../README.md)

## Before you start

The external trial is not open yet. We are completing operational checks and resolving a Google site-security warning. Express interest by emailing **mohamedramadan1313@gmail.com**; access details will be sent only after the launch gates pass. Do not bypass a browser warning.

No server administration is required of a trial reviewer. You will receive an assigned account, a link, an operating window, and an explanation of the trial limits. Do not share your account with another organization. Start with a public, historical, or synthetic tender and proposal that you are permitted to upload.

The prototype supports Arabic review workflows and English document examples. Some interface labels remain Arabic even when English is selected. We are improving this during the pilot. Screenshots in this guide are real application screens using synthetic data.

## 1. Sign in

Open your assigned link during its operating window. Enter the username and password supplied privately. Never put credentials in a GitHub issue or feedback email. If the site shows that evaluation is unavailable, wait for the announced window or contact support; repeatedly submitting the form will not start the server.

## 2. Prepare the tender and supplier submissions

Create a tender record. Add its requirements and the supplier submissions you want to review. Keep each supplier's documents with that supplier's submission. Classify files by their actual purpose: technical proposal or financial proposal.

After uploading, wait for processing to finish. Inspect the extracted text and requirement list. Scanned, rotated, low-resolution, redacted, or table-heavy documents may need additional review. If text is missing or a requirement was extracted incorrectly, correct the inputs before running an evaluation. An incorrect extraction can affect every subsequent conclusion.

For your first trial, use a small document and a few clear requirements. For example: a requirement for at least 500 TB and an explicitly offered capacity of 504 TB. This is a workflow exercise, not a full procurement benchmark.

## 3. Choose what to evaluate

Open the evaluation workspace for the tender. In **حدد النطاق والأطراف والبنود** (scope, suppliers, and requirements):

1. Select technical only, financial only, or both.
2. Select one supplier, several suppliers, or all available suppliers.
3. Select the requirements that actually belong to that scope.

The application does not assume that every requirement is technical or financial. A payment-term requirement should not be judged solely from an unrelated technical page. Check the selection before continuing.

## 4. Choose the review method

| Method | What it does | What to remember |
| --- | --- | --- |
| Human review | Gives the reviewer control of the assessment | Read the evidence and enter a reason for decisions. |
| Numeric rules | Applies supported, prepared numeric constraints | It is not a general language-understanding engine. |
| Local model | Processes the selected evidence using the configured local model | CPU-only processing can take several minutes per requirement. |
| Cloud model | Available only where enabled and configured by an administrator | External pilot access does not automatically include cloud processing or API credit. |

Click **عرض الموقف قبل التشغيل** (preview before starting). Check the chosen suppliers, number of requirements, ready documents, and warnings. Resolve blocked or incomplete inputs first. The preview is not the final assessment.

## 5. Start and open the evaluation

Click **بدء نسخة تقييم جديدة** (start a new evaluation version). A run may be queued, running, completed, failed, or interrupted. Do not repeatedly click Start because processing appears slow. Watch the run list.

When the run completes, click **فتح البنود** (open items) for the intended run. A failure is not a supplier-compliance decision. If a run fails, record its time and any error code and contact support.

## 6. Review the evidence, not just the label

For each requirement, inspect the explanation and document/page references. Confirm that the cited text describes the supplier's actual offer, rather than repeating the customer's request, describing another customer, or discussing a different product.

| Result | Meaning for the reviewer |
| --- | --- |
| C — Compliant | The result claims the requirement is met; verify the evidence. |
| PC — Partially compliant | Some required elements are supported, while others remain uncovered. |
| AC — Clarification needed | The evidence needs clarification before a confident decision. |
| NC — Non-compliant | The result claims a requirement is not met; verify the explicit basis. |
| NR — Insufficient evidence | Available evidence is insufficient; this is not automatically non-compliance. |
| NE — Not evaluated | The selected engine did not assess the requirement. |
| Contradiction | Conflicting statements require review. |

Matching a quotation to a page proves where it appears, not that it supports the conclusion. Missing information is different from an explicit statement that something is not included.

## 7. Record your decision

Select the item or items you intend to change. Choose the decision and write a meaningful reason. For bulk decisions, verify that the same reasoning genuinely applies to every selected item.

Click **حفظ القرار في نسخة جديدة** (save the decision in a new version). Check that the new version appears. Earlier results remain available for comparison; a reviewer decision should not silently erase the original assessment.

## 8. Export the right report

In the saved-runs table, select the completed version or versions you want to include. Choose **تنزيل التقرير المحدد — HTML قابل للطباعة PDF**. The downloaded HTML can be opened and printed, including printing to PDF where your browser supports it.

Check the tender, supplier, scope, date, and review version before sharing. Selecting an older run produces an older result even if you just saved a new decision. Exporting saved results does not require another model call.

## 9. Re-evaluate when inputs change

If documents, scope, or requirements change, review the inputs and start a new run. Keep the old result for traceability. Do not interpret differences between runs as proof of improvement without checking which inputs and engine changed.

## 10. Send useful feedback

Use the [feedback guide](FEEDBACK.md). Describe what you tried, what you expected, and what happened. Review screenshots and support exports before emailing them. Do not include confidential proposal content, passwords, API keys, or personal data.

## Common questions

**Can I evaluate only a technical proposal?** Yes: choose technical scope and its relevant requirements. Financial-only and combined scopes are also supported.

**Can I leave the decision to the model?** It can propose an assessment, but the trial is decision support. You remain responsible for reviewing it before procurement action.

**Does a high confidence label prove correctness?** No. Read the evidence and explanation.

**Can I use it all day?** The external pilot uses announced processing windows to control cost. The information site may remain available outside those windows.

**Where is the install package?** This repository is a showcase and guide, not a source or installer distribution. The hosted trial does not require users to install the application.
