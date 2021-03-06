# tapas-TEI-files/test_suite/
TEI test files (and some expected results)

Doubt this arrangement will remain, but for now:

* **F** = _fatal_: ill-formed, not XML
* **S** = _severe_: invalid TEI (including not in TEI namespace)
* **E** = _error_: valid, but rejected by TAPAS
* **W** = _warning_: acceptable, but likely won’t do what’s intended
* **D** = _debug_: poor practice detected
* **P** = _pass_: should pass all tests

Files are likely to change directories when we change our minds about
processing. :grin:

Note that this is not intended to be a comprehensive test suite.
Particularly for ill-formedness, I mostly need just one ill-formed
file to see that TAPAS rejects it. If you want a complete
well-formedness test suite, see
https://www.oasis-open.org/committees/xml-conformance/index.html.

