# Fumato Reorder — Case Study

## User journey
Past orders → select previous order → review/edit basket → validate current availability/pricing/customisation → confirm → checkout.

## Key failure states
- Restaurant closed
- Item unavailable
- Price changed
- Previous customisation no longer valid
- Accidental reorder

## Primary outcomes
- Completed valid reorder
- Time to reorder
- Funnel drop-off
- Repeat frequency

## Guardrails
- Substitution/removal rate
- Accidental-order rate
- Refund rate
- Support-contact rate
- Satisfaction

## Experiment framing
A reorder treatment should only be considered successful if it improves completion or speed **without** creating unacceptable increases in accidental orders, substitutions, refunds or support contacts.

## Product lesson
The difficult work often lives in exception handling rather than the happy-path button. A one-tap reorder should never silently bypass current price, availability or customisation validation.

## Attribution
NextLeap team project. This repository documents the product/analytics case and should not imply that a production Fumato backend was built.
