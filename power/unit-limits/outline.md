# Unit Limits

* draw X & Y axes - label vertical Power (MW), label horizontal Time (t)

## Economic Minimum

* This is the lowest that a generating resource can be online economically
* This value is important because this is the output level a generating resource will be at if it committed either by ISO or by self-committing or self-scheduling
* A generator that has been committed will operate at least at this level until it becomes a marginal resource and gets dispatched.
* Some generators have an Economic Minimum that is exactly the same as its economic Maximum - this means that a resource is "not dispatchable" 
* Generators that are operating below their ecomin are either starting up or shutting down
* once a generating resource has reached its ecomin and can respond to dispatch orders from ISO it will call ISO and "release for dispatch"

## Economic Maximum

* This is the highest that a generating resource can operate economically.
* This doesn't mean that a generator cannot output more than its EcoMax, in fact there is typically some range above the ecomax that can be available (RTHOL)
* Generators capable of dispatch operate between their ecomin and ecomax

## Real-time High Operating Limit

* This the absolute maximum that a generator can output in the current conditions 
* This value can change from day to day

## Emergency Minimum

* This is the lowest that a generator can safely operate in the event of a Minimum Generation Emergency - that is a condition where the electric generating supply is greater than the electrical demand
* This operating limit is only available to the ISO system operators when a Minimum Generation Emergency has been declared

## Dispatchable Region

* Generators that are capable of being dispatched are sent desired dispatch points at their ecomin, at their ecomax, or somewhere in between

## What's Next

* unit commitment
* unit control modes
