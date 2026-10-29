# Animation sources

The README uses the four GIF URLs supplied by the user from [Cool GIFs for GitHub](https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub):

- [Facebook](https://user-images.githubusercontent.com/74038190/235294010-ec412ef5-e3da-4efa-b1d4-0ab4d4638755.gif).
- [LinkedIn](https://user-images.githubusercontent.com/74038190/235294012-0a55e343-37ad-4b0f-924f-c8431d9d2483.gif).
- [Instagram](https://user-images.githubusercontent.com/74038190/235294013-a33e5c43-a01c-43f6-b44d-a406d8b4ab75.gif).
- [Intro illustration](https://user-images.githubusercontent.com/74038190/235224431-e8c8c12e-6826-47f1-89fb-2ddad83b3abf.gif).

These images load directly from GitHub's asset hosting. Their live playback has not been verified locally.

`intro.svg` fills the left tile with blue lettering. A persistent outline keeps the word visible while the solid fill and underline type across it. The reveal and caret animate with CSS transforms and opacity over a six-second loop, with a pause on the completed word. Reduced-motion preferences show the complete title and hide the caret; social links select their local static icons. The extra illustration uses the supplied GIF directly in a large right-hand tile spanning the title and combined experience box. The footer places the achievement and larger social icons on the left, with large blue focus areas in `focus.svg` on the right.

The bio is native README text, and the technology packs remain local SVGs.
