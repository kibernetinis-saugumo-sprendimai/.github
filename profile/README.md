# SafeStack CANON

SafeStack CANON is the **single source of truth** for the SafeStack ecosystem.

It defines **what is trusted**, **what is valid**, and **how integrity is verified**.
This repository is **read-only by design**.

---

## What this is

- A canonical reference for SafeStack system integrity
- Cryptographic hashes and signatures
- Verification rules and trust boundaries
- Architecture and system invariants

If something matches the CANON → it is trusted.  
If it does not → it is not SafeStack.

---

## What this is NOT

- Not an application
- Not a tool
- Not open for modification
- Not community-driven

Tools may change.  
Implementations may evolve.  
The CANON stays stable.

---

## How it works

1. CANON defines **trusted state**
2. Systems and nodes verify themselves against it
3. Any change **invalidates trust** until re-established and re-signed

Trust comes from **verification**, not from promises.

---

## Contents

- `CANON_HASHES.md`  
  Canonical hashes of trusted artifacts

- `CANON_HASHES.md.asc`  
  Cryptographic signature of the hashes

- `canon_verify.md`  
  How verification is performed

- `safe_stack_architecture_map_v2.md`  
  Canonical architecture and trust boundaries

- `safe_stack_mvs_minimal_viable_system.md`  
  Minimal viable definition of a SafeStack node

- `Federuota_autonominiu_mazgu_sistema.md`  
  Federated autonomous node model

---

## Rules (important)

- This repository has **no license on purpose**
- Reading and verification are allowed
- Modification means **it is no longer CANON**
- Modified copies must never be presented as SafeStack CANON

---

## Status

Stable.  
Immutable.  
Versioned via signed tags.

If it works only by following instructions,  
it is not understood yet.

Breaking systems is part of learning.  
Breaking the CANON means leaving the system.
