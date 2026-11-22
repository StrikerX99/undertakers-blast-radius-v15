# Undertakers Blast Radius V15

Build the extracted directory with `docker build --platform linux/amd64 -t undertakers-v15 .`. Commit these files at the root of the team repository. The selector reads the numbered test catalog and independent patches from `/data` and writes a worker assignment per patch.

The nine committed JSON maps record only the pristine SQLGlot revision `eb11aec4be8cb2122afe713a4816662c3f0fb2fa`. They cover executed code, fixture and setting reads, parser dispatch keys, stages of the native executor test, and the generator modules used to produce its reference SQL. Every patch is analyzed at runtime. Build steps derive additional indexes and time native checks.

A change to a parser table can affect a test that looked up a changed string, including unsuccessful lookups. The selector follows those reads and keeps opaque and reflective consumers. For a generator helper referenced by a dispatch table, it follows the affected entries for supported callbacks. For a deleted validation guard, it checks the original executed statements and their readers. Clearing an executor suite on this path also requires a matching cold trace of that suite, including work in subprocesses.

When an optimizer edit reaches the TPC-DS executor, the selector compares two baseline traces to identify the affected queries. For eligible patches it executes the changed optimizer work and compares the outputs to the pristine expressions. The time budget depends on how much omitting that test would reduce the complete worker schedule. If the check is inconclusive, the test stays eligible for scheduling.

For a broad parser or generator selection, the selector can import both the pristine and patched dialect classes, resolve the effective methods, and identify the tests that can reach a changed implementation. For eligible generator edits that leave TPC-DS unresolved, it checks the actual SQL produced on the recorded fixture inputs. This check gets a CPU budget based on the cost of the worker schedule after removing that test. Unrecognized effects or incomplete verification retain the candidate.

The worker allocator evaluates up to eight workers using the organizer's startup and load costs. The separate comparison archive contains the local scorer, independent inputs, labels, and receipts.
