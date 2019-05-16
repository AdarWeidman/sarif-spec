# Editor's report

Laurence J. Golding and Michael Fanning

This report describes the changes that were made after the first CSD.2 e-ballot was approved by the TC (May 8th, 2019) and before the second CSD.2 e-ballot was opened (May 16th, 2019).

- [Issue #398](https://github.com/oasis-tcs/sarif-spec/issues/405): "Write an Appendix on how a consumer decides if a run has failed"

- [Issue #405](https://github.com/oasis-tcs/sarif-spec/issues/405), "Post-CSD.2-ballot editorial changes".

    - Per @kupsch: Fix the example on p. 98. See Jim's [comment](https://www.oasis-open.org/apps/org/workgroup/sarif/ballot.php?id=3387#) on the ballot.

        NOTE: This is the only comment that was received on the CSD.2 ballot.

    - Per Yekaterina:

        - §3.20.21, "This is importance" => "This is important".

        - §3.31.3: '"fullyQualifiedName property' => 'fullyQualifiedName property'
    
            NOTE: @kupsch also reported this. It had already been fixed.

        - §3.58.4: "of zero of zero or more" => "of zero or more".

            NOTE: The CSD.2 draft incorrectly said "of one". The schema is correct (`"minItems": 0). This is now fixed.

    - Per @kupsch: In describing properties that default to -1 (meaning "not set"), describe it like this: "**SHALL** default to -1, which indicates the value is unknown (not set)."

- [Issue #406](https://github.com/oasis-tcs/sarif-spec/issues/406), "tool.driver required inconsistent with externalization"

- [Issue #407](https://github.com/oasis-tcs/sarif-spec/issues/407), "Add more artifact.roles values"

- [Issue #408](https://github.com/oasis-tcs/sarif-spec/issues/408), "Missing condition in message lookup procedure"

- [Issue #410](https://github.com/oasis-tcs/sarif-spec/issues/410), "3.38.3 location property example includes "message" in the wrong place"

- [Issue #411](https://github.com/oasis-tcs/sarif-spec/issues/411), "Spec mentions "subset" relationship rather than "superset" in several places"

- [Issue #415](https://github.com/oasis-tcs/sarif-spec/issues/415), "logicalLocation.name should not be required"

- [Issue #416](https://github.com/oasis-tcs/sarif-spec/issues/416), "Loosen prohibition of RMS-deducible information in partial fingerprints"