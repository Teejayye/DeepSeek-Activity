# AI Asset Auction

A 10-minute classroom game for Team G's presentation on **DeepSeek and open-source AI** (Digital Innovation & Entrepreneurship, Tutorial 5).

**Play:** https://teejayye.github.io/DeepSeek-Activity/

## The game

Three groups are rival AI start-ups. Each group starts with €100M. Six assets from the DeepSeek case are auctioned one at a time. Each asset has a hidden real value.

1. Each group gets 30 seconds to agree on one bid and send it from its phone.
2. All bids are revealed at once. The highest bid wins and pays. Other groups pay nothing.
3. If two groups tie for the highest bid, nobody gets the asset.
4. The winning group explains its bid. Then the real value is revealed.
5. **Final score = money left + real value of your assets.** The highest score wins.

Each value reveal links the asset to a week 5 reading: Agrawal et al. (2017), Cromwell et al. (2023), Hurwitz & Kirsch (2018), Mollick & Euchner (2023), O'Neil (2017), and the Edureka video.

## How to run it

- Open the link on the presenting laptop and put it on the projector.
- One phone per group scans the QR code and picks its group. Groups lock when the auction starts.
- If phones can't connect, you can type bids on the laptop instead.
- Use **Reset game** at the bottom of the screen before class.

## Tech

One `index.html` file, hosted on GitHub Pages. Phones connect directly to the laptop through [PeerJS](https://peerjs.com). There is no server and no login.
