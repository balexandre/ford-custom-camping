# Transit Custom Camp Kit

Plans for turning a wheelchair-accessible Ford Transit Custom into a weekend camper, without taking away what makes it wheelchair-accessible.

**Open the planner: https://balexandre.github.io/ford-custom-camping/**

## The van

- Ford Transit Custom, built in 2023, converted for wheelchair use.
- A **wheelchair lift** folds up inside the rear doors, so the back of the van can't be used for loading or for a kitchen.
- A **seat** on the right, just behind the sliding door, is fixed and can't be removed. It folds closed, and folded it is low enough to build a bed over.
- **Two pairs of floor rails** run along the floor, used for anchoring seats and wheelchairs.

## The idea

A removable kit that bolts to the floor rails that are already there:

- A **bed** that runs front to back, from behind the front seats to just in front of the folded lift, built over the closed seat.
- A **drawer unit** under the bed, lined up with the sliding door. The drawers pull out sideways through the door, which makes an outdoor kitchen and storage that are easy to reach.
- A **storage compartment** behind the drawers, along the left wall, reached by lifting a deck panel. It suits a leisure battery, a water can or bedding.
- **No drilling.** Everything is held by seat-rated fittings in the existing rails, so the wheelchair conversion stays as it was approved, and the kit comes out when the van is needed for the wheelchair.

Seen from above, with the front on the right:

```
  REAR                                                 FRONT
  +--------+--------------------------------------+--------+
  |        |                          +---------+ |        |
  |  lift  |       bed over the       | storage | |  front |
  |(folded)|       whole floor        +---------+ |  seats |
  |        |  +-------------+         | drawers | |        |
  |        |  | seat, closed|         |  v   v  | |        |
  +--------+--+-------------+---------+---------+-+--------+
                                   < sliding door >
                                   drawers pull out
```

## Using the planner

The planner is a single web page. Type in the van's measurements and it redraws everything to scale:

- a **plan**, a **side view** and a **cross-section** through the drawers
- **checks** that flag problems: a mattress that doesn't fit, too little headroom, drawers that are too long, the seat in the way, missing anchor points
- a **cut list** for the plywood and the aluminium frame, with a sheet count
- a **hardware list** and a **weight estimate**

The values it opens with are **examples**, taken from brochure figures and typical conversions. Replace them with real measurements. Every length is measured back from the front seats.

The measurements that matter most, in order:

1. **The seat's height when closed.** It sets the bed height, and the bed height decides whether you can sit up in bed.
2. **Floor to ceiling** above the bed area.
3. **The folded lift's depth** inside the van, including arms, handles and the hand pump.
4. **Floor length** from the back of the front seats to the rear doors.
5. **Where the rails are**, measured from the door-side wall, plus a photo of a rail fitting so matching ones can be bought.
6. **The sliding door opening**: where it starts, how wide it is, and how far the closed door reaches inside.
7. **The wheel arches**: where they start, how long and how high.

**Copy measurements** puts all values on the clipboard as plain text, ready to send to someone. Measurements are saved only in your own browser and are never uploaded.

## What the example numbers show

With the example values (low roof, seat about 48 cm high when closed, 10 cm mattress):

- A 190 × 140 cm mattress fits, with room to spare in front of the lift.
- Two 1 m drawers fit under the bed, with a storage compartment about 57 cm deep behind them.
- When pulled out, the drawer top is about 1 m off the ground, a comfortable height for cooking outside.
- **Headroom is the weak point.** There are only about 77 cm from the mattress to the ceiling, and most adults need 85–90 cm to sit upright. Fine for sleeping, a slouch for sitting. A high-roof van doesn't have this problem.
- The whole kit weighs roughly 100 kg in 18 mm plywood. 15 mm poplar and lightening holes bring it down a lot.

## Building it safely

- **Anchor only to the rails**, with seat-rated fittings that match the rail system. Seat anchorages are tested at 20 g, so even a 70 kg kit can push forward with more than a tonne in a crash.
- **Use locking drawer slides**: they lock shut for driving and lock open on a slope while cooking.
- **Keep the lift usable.** Its hand pump and emergency release must stay reachable with the bed in place.
- **Cook outside**, on the pulled-out drawer.
- **Ventilate under the mattress** (holes in the deck or an anti-condensation mat) to keep mould away.
- **Check the paperwork.** A removable kit held by the existing rails is normally treated as secured load. A permanent motorhome conversion needs approval from the vehicle authority.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The planner. One self-contained page, no build step. Open it in a browser or serve it with GitHub Pages. |
| `README.md` | This file. |

This is a planning aid, not an engineering sign-off. Check every size against the real van before cutting anything, and ask the company that did the wheelchair conversion before attaching anything to its rails.
