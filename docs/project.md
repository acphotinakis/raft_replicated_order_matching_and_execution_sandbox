# Raft-Replicated Order Matching and Execution Sandbox

A strategy plug-in consumes a bounded trades/quotes trace and submits simulated orders to a three-node. Raft-replicated log. Every replica applies the committed log to the same deterministic matching and portfolio state machine; leader failure is injected during replay.

## ● Question: Can replicated-log agreement preserve identical committed order, fill, and portfolio state

after leader failure?

## ● Course alignment: Raft, leader election, heartbeats, log replication, state-machine replication, crash recovery, consensus.

## ● Quant value: Tests auditability and deterministic execution of simulated orders.

## ● Foundation: Ongaro and Ousterhout, In Search of an Understandable Consensus Algorithm.
