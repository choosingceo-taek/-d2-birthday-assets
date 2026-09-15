# d2-birthday-assets

Public image assets for the birthday notification Adaptive Card posted to Microsoft Teams.

Teams renders an Adaptive Card `Image` only from a URL it can reach without
authentication, and the service repository is private — so the card's sender
avatar is served from here.

| File | Use |
| --- | --- |
| `icon-192.png` | Sender avatar in the card header, rendered at 36px |
| `icon-512.png` | Source size, kept for regenerating the smaller file |

Nothing here is specific to a person or a team. The roster, the schedule and
the code live in the private service repository.
