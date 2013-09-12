# Rampant Emergence
1. Don't do stupid thing ([Anti-pattern Catalogue](http://c2.com/cgi/wiki?AntiPatternsCatalog))
2. Be careful of architectural smearing- using things in multiple places that aren't for a single purpose
3. Stay in sync with upgrades- Rails, etc
4. Keep domain logic DRY
5. Malleability
6. loose coupling at integration points
7. Coarse-grained components/serviecs
8. know your (product) goals- Pivot friendly architecture

##### Make decisions at the last possible moment

### Green->Brown stage
* Add semi-permanent technical debt cards
* switch emergent design styles
* harvesting model for reuse
* Gradually escalate refactoring effort

### "No Design" / Prefer dynamic over Static
No matter how much you try, requirements evolve chaotically, bedrock assumptions become malleable

* Don't think of the application of an equation
* …it's a snapshot of a process
* Think about incorporating a time element


### Annealing
Greenfield => Emphasize Malleability
Brownfield => Emphasize Annealiability