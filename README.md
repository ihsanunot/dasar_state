# Managing state

We’ll give examples of the different ways of managing state by creating three simple examples: **TapboxA, TapboxB, and TapboxC.**

- https://docs.flutter.dev/ui/interactive#managing-state

---

The examples all work similarly—each creates a container that, when tapped, toggles between a green or grey box. 

The _active boolean determines the color: green for active or grey for inactive.
---

**The _TapboxAState class:**

* Manages state for TapboxA.

* Defines the _active boolean which determines the box’s current color.

* Defines the _handleTap() function, which updates _active when the box is tapped and calls the setState() function to update the UI.

* Implements all interactive behavior for the widget.

