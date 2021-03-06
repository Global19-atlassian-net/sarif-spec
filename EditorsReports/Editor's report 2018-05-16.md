# Editor's report

Laurence J. Golding and Michael Fanning

Presented at TC Meeting #17, May 16th, 2018

1. After being approved as amended at the last TC meeting (#16), the following spec changes were merged into the provisional draft:

    1. [Issue #122](https://github.com/oasis-tcs/sarif-spec/issues/122): "Clarify guidance for 'partialFingerprints' components"

    1. [Issue #126](https://github.com/oasis-tcs/sarif-spec/issues/126): "Add result.fingerprints array"

    1. [Issue #134](https://github.com/oasis-tcs/sarif-spec/issues/134): "conversion.analysisToolLogFileLocation should be an array"

    1. [Issue #136](https://github.com/oasis-tcs/sarif-spec/issues/136): "Make sure result.id explicitly notes its relevance to automation/results management systems"

    1. [Issue #137](https://github.com/oasis-tcs/sarif-spec/issues/137): "Support annotating image attachments"

    1. [Issue #139](https://github.com/oasis-tcs/sarif-spec/issues/139): "Don't require codeFlowLocation.location"

    1. [Issue #145](https://github.com/oasis-tcs/sarif-spec/issues/145): "For symmetry, define a logicalLocation object"

    1. [Issue #147](https://github.com/oasis-tcs/sarif-spec/issues/147): "Rename suggestion: toolFingerprintContributions -> partialFingerprints, computedFingerprints -> fingerprints"

    1. [Issue #148](https://github.com/oasis-tcs/sarif-spec/issues/148): "update stableId to allow for build configuration/other details"

    1. [Issue #154](https://github.com/oasis-tcs/sarif-spec/issues/154): "Define a "result management system" conformance profile"

    1. [Issue #155](https://github.com/oasis-tcs/sarif-spec/issues/155): "Remove annotations object; use regions instead"

1. I made the following changes at editorial discretion:

    1. Clarify a circumstance where a `message` object contains _only_ an `arguments` property.

    1. Use the term "hierarchical" instead of "namespaced" for strings of the form `"component / component..."`.

    1. [Issue #156](https://github.com/oasis-tcs/sarif-spec/issues/156): "Improve example of messages with placeholders and consider putting it in a more prominent location"

1. The formal spec language for the following additional issues was made available for review on the specified dates, and we will move their adoption in today's meeting:

    1. [Issue #93](https://github.com/oasis-tcs/sarif-spec/issues/93): "Problems with regions" -- made available on May 11th, 2018.

    1. [Issue #103](https://github.com/oasis-tcs/sarif-spec/issues/103): "Specify handling of line breaks" -- made available on May 5th, 2018.

    1. [Issue #138](https://github.com/oasis-tcs/sarif-spec/issues/138): "Consider a download/install uri for the tool" -- made available on May 1st, 2018.

    1. [Issue #141](https://github.com/oasis-tcs/sarif-spec/issues/141): "Consider adding timestamp to file object" -- made available on May 1st, 2018.

    1. [Issue #143](https://github.com/oasis-tcs/sarif-spec/issues/143): "Add 'returnType', 'parameter' and 'local' to logical location kind enum" -- made available on May 1st, 2018.

    1. [Issue #149](https://github.com/oasis-tcs/sarif-spec/issues/149): "Support nested graphs" -- made available on May 10th, 2018.

    1. [Issue #153](https://github.com/oasis-tcs/sarif-spec/issues/153): "Clarify treatment of backslashes and square brackets with respect to embedded links" -- made available on May 4th, 2018.

    1. [Issue #157](https://github.com/oasis-tcs/sarif-spec/issues/157): "Clarify requirements on tool.semanticVersion" -- made available on May 4th, 2018.

    1. [Issue #159](https://github.com/oasis-tcs/sarif-spec/issues/159): "Id property renames" -- made available on May 8th, 2018.

    1. [Issue #160](https://github.com/oasis-tcs/sarif-spec/issues/160): "Roles for edited files" -- made available on May 11th, 2018.

    1. [Issue #161](https://github.com/oasis-tcs/sarif-spec/issues/161): "Expand code flows to represent dynamic execution events" -- made available on May 10th, 2018.

    1. [Issue #162](https://github.com/oasis-tcs/sarif-spec/issues/162): "run.automationId is namespaced" -- made available on May 7th, 2018.

    1. [Issue #163](https://github.com/oasis-tcs/sarif-spec/issues/163): "Add result.workItemLocation" -- made available on May 8th, 2018.

    1. [Issue #165](https://github.com/oasis-tcs/sarif-spec/issues/165): "Add run.description" -- made available on May 8th, 2018.

    1. [Issue #166](https://github.com/oasis-tcs/sarif-spec/issues/166): "Define an "engineering system" conformance profile" -- made available on May 8th, 2018.
