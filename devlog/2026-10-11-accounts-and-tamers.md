# Accounts, tamers and 35 looks

*2026-10-11*

The title screen has a new row: **ONLINE**. It opens a panel for logging in or making an account,
drawn over the original title in the game's own style.

![Log in and new account](../misc/screenshots/new-account.jpg)

Behind it is a real server: a gateway on Linux, a PostgreSQL database, an encrypted connection
(TLS 1.3), and passwords stored only as Argon2id hashes. Wrong passwords slow down further tries
from the same place, without locking you out of your own account.

## Your tamer

After the first login you make your tamer: a name, a partner, a Guard Team and a look.

![Create your tamer](../misc/screenshots/tamer.jpg)

- **Partners:** Agumon (Vaccine), Patamon (Data) or DemiDevimon (Virus), the three rookies of the
  original start.
- **Guard Teams:** Gold Hawk, Blue Falcon or Black Sword. The team is your faction for chat and
  ladders; it gives no power.
- **Looks:** 35 tamer looks made from the people of Digital City, shown in 3D next to your
  partner. Looks that never had a running animation in the original game borrow the player's run,
  so everyone moves the same way.

The server then builds your start profile from the game's own data: your partner, the first
Digi-Beetle, and the city as it is after the opening. "Enter the city" downloads it and you walk
out of the Main Gate.
