# Remap Manifest — mycelium-core → core

_DN-109 §5.2 provenance ledger. Guarantee: **Declared** — this records proposed/performed structural and idiom choices; it does not certify them (no guarantee-tag upgrade from the manifest's existence alone, VR-5). Rendered from `remap` in `summary.json` — this file is a pure projection, never a second source of truth._

## Nodules (19)

| Target nodule | Operation | Safety | API surface changed | Identity neutral | Sources | Rationale |
|---|---|---|---|---|---|---|
| `core.binary` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/binary.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.bound` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/bound.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.cert_mode` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/cert_mode.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.content` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/content.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.data` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/data.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.datum` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/datum.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.guarantee` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/guarantee.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.id` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/id.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/lib.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.lower` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/lower.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.meta` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/meta.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.node` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/node.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.prim` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/prim.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.recon` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/recon.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.repr` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/repr.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.ternary.big_ternary` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/ternary/big_ternary.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.ternary` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/ternary/mod.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.value` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/value.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `core.wrapping` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-core/src/wrapping.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |

## Idiom choices (0)

_(none in this run — v0 Mechanical-only auto-fire with no located idiom-choice instrumentation yet; see DN-109 §7-e and this module's doc comment)_
