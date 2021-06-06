### Follow this steps to run Hello World

0. Install nix-shell (https://developer.holochain.org/docs/install/)
1. Clone this repository
2. Go to root folder where you see `default.nix` and run `nix-shell` (It takes a lot of time just for the first time.)
3. Go to tests folder and run `npm i`
4. In the tests folder run `npm test`
In case you run into compile errors - esp. relating to lazy_static, you may have to manually set the toolchain to the rust nightly release channel
5. From the tests folder in nix-shell run `rustup toolchain install nightly`
6. And then `rustup override set nightly` and then run `npm test` again.
___________

### This video of Holochain-in-Action can help for better understanding:
https://www.youtube.com/watch?v=1I4-5ujGxmY&list=PL2hOZGg8QnUDiTkJF2CD2Fu1D9F6KbsmB&index=2&t=837s

__________

If you would like to participate and improve it, please send your PR.
