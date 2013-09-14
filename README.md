heavy
=====

Event Driven, Hierarchical State Machine extensions for Rails ActiveRecord, ActionController and Routing

1. Need a state machine extension for ActiveRecord.   Haven't seen too many I like
2. DSL in ActiveRecord that supports HSM sematics between Models and their associations
3. DSL supports specification of state context (AR attributes), sub-states, state enter, exit, and event transition callbacks
4. DSL supports specification of events and next state.
5. DSL supports escalation of events from sub-states to outer state context.
4. DSL supports wait state/ timeout definition, a state that persists until an external event is routed to it.
5. DSL supports split/rendezvous/ timeout definition, allowing a common wait point for multiple sub states to transition
6. DSL supports event guards boolean expressions.
7. DSL supports param-based routing of events and param pattern matching
8. Counters and Timings (with histograms) instruments all states and wait states.
