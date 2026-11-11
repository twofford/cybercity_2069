# Vehicles

Vehicle stats, prices, crashes and chases. See [[Rules Reference]] for combat and [[Equipment]] for everything else you can buy.

## Prices

Prices are roughly today's price for the same vehicle, times 8.15, rounded (see Money in [[Rules Reference]]). Few people pay cash. Vehicles can be financed on the same terms as chrome: 10% down, then 5% a month (see [[Chrome]]). Miss two payments and the lender sends someone to take it back.

| Vehicle                        | Usual maker           | Move   | HP  | Armor | Riders' cover    | Good at                             | Used                         | New          |
| ------------------------------ | --------------------- | ------ | --- | ----- | ---------------- | ----------------------------------- | ---------------------------- | ------------ |
| Electric bike                  | Budget EV             | 60 ft  | 6   | 0     | None             | Traffic, alleys                     | $6,000                       | $12,000      |
| Electric moped                 | Budget EV             | 60 ft  | 8   | 0     | None             | Traffic                             | $12,000                      | $25,000      |
| Motorcycle                     | Budget EV             | 120 ft | 12  | 0     | None             | Traffic, open road                  | $50,000                      | $100,000     |
| Car                            | Budget EV, Heavy-duty | 120 ft | 30  | 2     | Partial          | Open road                           | $65,000 (beater) to $200,000 | $400,000     |
| Luxury car                     | Luxury                | 120 ft | 35  | 4     | Partial          | Arriving well                       | $800,000                     | $1,600,000   |
| Van or pickup                  | Heavy-duty            | 90 ft  | 40  | 2     | Partial          | Hauling people and cargo            | $250,000                     | $450,000     |
| Armored SUV                    | Heavy-duty            | 90 ft  | 60  | 10    | Full, windows up | Taking hits                         | —                            | $2,000,000   |
| Armored limousine              | Executive             | 90 ft  | 60  | 12    | Full, windows up | Never touching the street           | —                            | $6,500,000   |
| Motorboat                      | Various               | 120 ft | 25  | 0     | None             | Water                               | $200,000                     | $400,000     |
| Light helicopter               | Luxury                | 300 ft | 40  | 4     | Partial          | Getting over everything             | $3,000,000                   | $5,000,000   |
| AV (armored, vertical takeoff) | Executive             | 300 ft | 60  | 10    | Partial          | Flying where helicopters can't land | —                            | $10,000,000+ |
| Scout drone                    | Fleet                 | 60 ft  | 3   | 0     | —                | Watching                            | —                            | $8,000       |
| Armed drone (pistol or SMG)    | Military              | 60 ft  | 10  | 2     | —                | Guarding                            | —                            | $200,000     |

- **Move** is how far the vehicle goes on one Move action. In zones, a ground vehicle crosses two zones per Move; aircraft cross four.
- **Vehicle armor can go past 8,** the cap for people. An armored SUV shrugs off most small arms.
- **Drones** are flown with Piloting, by radio. A jammer grounds them (see Hacking in [[Rules Reference]]).

## Makers

The table's stats already include the usual maker's trait. Give each kind of maker a name that fits your setting.

| Maker      | Makes                                                             | Trait                                                     |
| ---------- | ----------------------------------------------------------------- | --------------------------------------------------------- |
| Budget EV  | Cheap electric bikes, mopeds, motorcycles and city cars           | **Connected:** always online, so one step easier to hack  |
| Heavy-duty | Cars, pickups, vans and armored SUVs                              | **Rugged:** crashes deal half damage to the people inside |
| Luxury     | Luxury cars and helicopters                                       | **Armored:** +2 armor over an ordinary version            |
| Executive  | Armored limousines and AVs, for people who never touch the street | **Armored:** +4 armor over an ordinary version            |
| Fleet      | Drones                                                            | **Fleet:** the maker can take it over remotely            |
| Military   | Armed drones                                                      | **Hardened:** one step harder to hack                     |

## In a fight

- **Driving:** the driver uses AP like anyone else. Move moves the vehicle its Move distance. Eyes on the Road keeps it under control, and Evade swerves it (see Actions in [[Rules Reference]]).
- **Passengers** act normally. Shooting from a moving vehicle is −5 for the shooter.
- **Shooting at a vehicle:** pick the vehicle or someone inside it. People inside get the riders' cover from the table. Vehicles are never small targets, except drones.
- **Damage** works as it does for people: subtract the vehicle's armor from each hit.
- **At 0 HP** the vehicle is wrecked. A parked one is just scrap. A moving one crashes.
- **Ramming** is an Attack: the driver rolls Reflexes + Driving at the usual difficulty. Damage by the rammer's size: bike or moped d6 ×2, motorcycle d8 ×2, car d10 ×2, van, SUV or bigger d12 ×2. The rammer's vehicle takes half.
- **Crashing:** everyone aboard takes d8 ×2, or d10 ×2 with no cover (bikes, motorcycles, boats). Armor applies.
- **EMP** stalls any vehicle in the blast until the end of its next turn.
- **Hacking:** vehicles are devices, and an armored corp van is Hard to hack. See Stall and Hijack in [[Programs]].

## Repairs

- **In the field:** Tech + Engineering with a toolkit, Medium. Restores 2d4 HP, or 4d4 on a full success. Takes a few minutes, so it's rarely possible mid-fight.
- **At a garage:** back to full HP for about 10% of the vehicle's price. Takes a day.

## Chases

A chase uses the range bands as the gap between the two vehicles: Close, Short, Medium, Long, Extreme, then gone. Most chases start at Medium. The same bands set the range for anyone shooting between the vehicles.

Chase rounds are combat turns, so passengers can shoot, hack and throw things. Once per round, the PC driver rolls **Reflexes + Driving** (Piloting for aircraft, boats and drones), using their Move. The GM sets the difficulty from the road and the other driver: Easy for an empty road and a nervous amateur, Very Hard for rush hour on the expressway with a corp wheelman behind you.

- **Full success:** the gap moves one band your way. It moves two if your vehicle is good at this terrain and theirs isn't (a motorcycle cutting through stopped traffic).
- **Partial success:** the gap moves one band your way with a catch (you clip something and the vehicle takes damage, a passenger loses their shot, you end up somewhere you didn't want to be), or it moves and +1d4 Tension.
- **Failure:** the gap moves one band their way, or you hold the gap with a complication, or it holds and +2d4 Tension.

**Running:** get past Extreme and you've lost them. **Chasing:** get to Close and you can ram them, shoot at Close range or force them off the road.
