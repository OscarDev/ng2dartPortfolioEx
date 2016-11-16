# ng2dartPortfolioEx
To run on local host:

pub get

pub serve

This project a handful of nested MaterialExponsionSetPanels to organize a portfolio in four groups.

This is the first thing to come from exploring the new angular2dart components released by google.
There isn't a sidebar yet, and I'm not too confident that it'll hold together well if components are stacked side to side, so I just did a simple one-column layout.

Things I discovered:
An overarching MaterialExponsionSetPanelSet causes only one child MaterialExponsionSetPanel to be open in a set.

The ScoreboardComponent example in the documentation wasn't scrollable as it explicitly declares, or I just haven't added enough ScorecardComponents to see scrollability.

The FixedMaterialTabStripComponent seemed to be a standalone component that could be initialized due to the 'Component suffix' but the FixedMaterialTabStripComponent is used in a higher upper component. Same thing can be said about the TabButtonComponent only being used by the tab strip component. Trying to force an initialization of these two with the selector failed at time. I'm still learning though. Hope make a webapp with these components in the future :)
