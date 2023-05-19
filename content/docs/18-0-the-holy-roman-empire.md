---
title: "18. The Holy Roman Empire (HRE)"
---

# 18. The Holy Roman Empire (HRE)

The Holy Roman Empire is an institution that wields great power, but it is a difficult beast to tame. It is a great responsibility, and its member states won't necessarily always bend to the will of their Emperor.

In the standard 1444 setup, Austria starts as the Holy Roman Emperor.

## 18.1 Imperial Authority

The Holy Roman Emperor has an Imperial Authority (`E`) ranging from 0 to +6, with different bonuses according to its level. Reducing `E` when it is already at 0, or increasing it when it is at +6, has no effect. In a 1444 setup, the Emperor starts with +3`E`.

`E` is capped at 1 + the current number of Elector Areas (see section 18.3).

### Increased Manpower and Income

The Holy Roman Emperor's `E` value is added directly to their `m` value. If Imperial Authority changes, the Emperor's Manpower Reserve must be adjusted accordingly, in Phase 5, Step A.

During Phase 4, the `E` value is also added directly to the Emperor's Tax Income. This additional Tax Income is not considered to be part of Base Tax Income, and it is not included when calculating `m`.

### Additional Bonuses

Each Round, during the Income & Upkeep Phase, the Emperor's `d` income (and potentially `0`) is affected by the `E` level.

| Current `E`      | Bonus |
|------------------|-------|
| **+1** or higher | May use *Defending the HRE* ability |
| **+2** or **+3** | +1`b` |
| **+4** or **+5** | +1`b` and +1`c` |
| **+6**           | +2`b`, +1`c`, and +`1` |

### Gaining/Losing Imperial Authority

The Emperor can increase their Imperial Authority by 1 step as an Action (by spending `a` equal to 1 plus their current `E` level), by defeating external attackers, and by reincorporating HRE Areas.

The Emperor can lose `E` as a consequence of failing in their duty to protect their Subjects and the HRE lands, or by aggressively expanding within the HRE.

| Event/Action | `E` |
|--------------|-----|
| Spend `a` = 1 + current `E` | +1 |
| Win War vs. non-HRE Aggressor | +1 |
| Reincorporate HRE Area | +1 |
| If below +3`E` upon Election | +1 |
| Refusing CtA from an Imperial Subject following a DoW by a non-HRE Aggressor | -1 |
| An Area leaves the HRE | -1 |
| Lose War vs. non-HRE Aggressor | -1 |
| Emperor Declares War on HRE Member without having a CB | -1 |
| Emperor enforces Full Annexation Peace Term on an HRE Member of the same State Religion | -1 |
| \# of Elector Areas falls below: current `E` – 1 | -1 per step |

## 18.2 Imperial Influence

There are 6 gray Imperial Influence cubes in the game. The Emperor has access to a number of Imperial `I` equal to `E`. They place Imperial `I` during setup, per setup instructions, and update the number of Imperial `I` available in Phase 5, Step B, based on the current `E`.

For most purposes Imperial `I` works just the same way as regular `I` but there are some exceptions:

- Imperial `I` is always placed or redistributed in Phase 5, Step B, and should always match `E` at that point.
- Imperial `I` must be placed in HRE Areas that contain at least 1 Province Owned by an NPR HRE Member.
- If an HRE Area with Imperial `I` leaves the HRE, that Imperial `I` is immediately removed from the board and returned to the Supply.
- Imperial `I` may not be removed for the purpose of the Subjugate Action.

## 18.3 HRE Lands

All Provinces and Areas inside the dotted HRE border are considered part of the HRE, unless a "Not HRE" token has been placed in the Area in question (see section 18.6).

For the HRE to retain its integrity and unity, the Emperor must make sure that HRE Provinces are owned by member states and not by external Realms.

### HRE Members / Imperial Subjects

All Realms whose Capital is inside the dotted HRE border are considered to be HRE Members unless there is a "Not HRE" token in their Capital Area. Member states that are not the Emperor are considered Imperial Subjects of the Emperor. PRs, NPRs, and Vassal Realms can be HRE Members.

### PRs as Imperial Subjects

In some scenarios, PRs may be playing as HRE Member states that do not hold the Emperor title (e.g., ›Netherlands or ›Brandenburg). The Emperor might also be a PR or they may be an NPR.

PR HRE Members may only leave the HRE if they have a Mission or Event that allows them to do so. They may not ***Research*** Government Ideas if `E` is +3 or higher.

As an Imperial Subject, every time the Emperor activates *Defending the HRE*, you must do -one- of the following:

- Exhaust 2`m` (max. ½ of total `m`)
- Lose 6`D` (max. ½ of Tax Income)
- Lose `1`
- Place a CB token on Aggressor's Capital

### Unlawful Province Occupants

If an HRE Province is Occupied, Owned, or Vassalized by an external Realm (one whose Capital is outside the HRE), that Realm is considered to be an Unlawful Occupant.

The Emperor has a permanent Imperial Liberation Casus Belli (see p. 22) against all such Unlawful Occupants. If an Area in its entirety leaves the HRE (as described below), these Provinces are no longer considered part of the HRE and the Emperor loses the Imperial Liberation Casus Belli for all Provinces in that Area.

Unlawful Occupants in the 1444 setup: ›Burgundy, ›Venice, and ›Denmark.

### Elector Areas

Elector Areas are indicated on the board by an Imperial eagle. These Areas are of extra importance to the Emperor, and to anyone with ambitions of becoming the next Emperor.

To count as an Elector Area, the Area must contain the Capital of -at least 1- HRE Member. If all such Capitals are Owned by Realms whose Capitals are in different Areas, the Area is not counted as an Elector Area.

## 18.4 Defending the HRE

When a non-HRE Realm Declares War on an Imperial Subject, if `E` is at +1 or higher, a PR Emperor will automatically receive a *Defensive CtA* from their Subject unless this Subject is at War with the Emperor.

A PR Emperor may accept such a CtA, as if from an Ally, following the 'Accepting a CtA' procedure (see p. 32), but also tagging the *Defending the HRE* slot on the Status Mat with a Tag chit. As long as the Emperor is still at War, this ability will be active. If a PR Emperor refuses such a CtA, instead of the normal effects of refusing a CtA, they immediately suffer a -1`E` penalty.

If a PR Emperor's own Capital is located inside the HRE, they may also activate the *Defending the HRE* ability when a non-HRE Realm Declares War on them directly.

### Imperial Manpower

Upon activating *Defending the HRE*, a number of NPR Units equal to the Emperor's total `I` in Elector Areas (including Imperial `I`) is added to the Imperial `m` pool on the Status Mat, up to a maximum of 8 Units.

The Emperor may use Imperial `m` in every Battle where they participate in HRE Areas, or any Areas of their Realm that are adjacent by Land to an HRE Area. They may, at the start of such Battles, add all of this `m` as Infantry Units that will fight alongside their Army, except in Battles where the Enemy facing the Emperor only consists of NPR HRE Members.

The Imperial Units work like Allied Units in the Battle, but are kept separate from any other Allied Units in the same Battle. Once the Battle is over, any surviving Imperial Units are returned to the Imperial `m` pool. These will be available in later Battles.

When the Emperor is at Peace again, in Phase 5, Step B, empty the Imperial `m` pool, and return any remaining NPR Units to the General Supply.

### Military Access in the HRE

While *Defending the HRE* is tagged, the Emperor, and anyone at War against the Emperor, has free Military Access (see p. 25) through all Areas within the HRE.

### Peace Resolution

While the *Defending the HRE* slot is tagged, PRs at War with the Emperor may not enforce Peace on any Imperial Subjects unless they have achieved a Victory over the Emperor in the War (see Victory Conditions on p. 29). Instead, Peace must be negotiated with the Emperor, who may agree to Peace Terms on behalf of their NPR Imperial Subjects as they would for any Active Allies.

If a War against an external Aggressor is won by the Emperor, they gain 1`E` if no HRE Provinces are ceded to external Realms.

If a War against an external Aggressor is lost by the Emperor, they lose 1`E`. If whole Areas thus leave the HRE, they will lose `E` due to this as well (see section 18.6).

## 18.5 Internal Wars

If the Emperor does not have a CB when Declaring War against one of their Imperial Subjects, they will lose 1`E` and must remove 3`I` from HRE Areas (in addition to the regular penalties for having no CB).

If an Imperial Subject Declares War on another HRE Member without a CB, the Emperor must place a CB token on the Capital of the Aggressor.

### Full Annexation by Emperor

If the Emperor enforces the Full Annexation Peace Term on an HRE Member of the same State Religion as themselves, they lose 1`E`.

## 18.6 Leaving & Rejoining the HRE

If all the Provinces in an HRE Area are -Owned- by external Realms (not Emperor, and with their Capital located outside the HRE), that Area will automatically leave the HRE. Place a "Not HRE" (`/`) token in the Area.

If an Area leaves the HRE, the Emperor loses 1`E`. Loss of `E` for Areas that leave as a direct consequence of an Event is accounted for in the Event effects.

### Reincorporating Areas

Whenever all Provinces in an Area that left the HRE are Owned or Vassalized by HRE Members or the Emperor, the Area is reincorporated into the HRE; remove the `/`.

To reincorporate Areas that are partially within the HRE border, only the Provinces within the border need to be Owned or Vassalized by HRE Members or the Emperor.

When an Area is reincorporated into the HRE, the Emperor gains 1`E`.

## 18.7 HRE Religion

**Advanced Rules**

At the start of the game, the official Religion of the HRE is Catholicism (as seen on the Status Mat). The HRE may only be Catholic or Protestant, or have no official Religion.

**Note:** The HRE's Religion cannot change until Age III, from which point onwards it is checked at the end of each Round:

- If all Elector Areas are Protestant but the HRE's Religion is not, the HRE turns Protestant (put token) and `E` drops by 1.
- If all the Elector Areas are Catholic, the HRE's Religion stays/becomes Catholic (remove Religion token, if any).
- If there are Elector Areas of multiple Religions, the HRE ceases to have an official Religion (place a Diverse Faiths token).

The Emperor is only allowed to ***Change State Religion*** if the HRE has changed its official Religion to another Religion than that which is currently the Emperor's State Religion.

If the Emperor adopts Revolutionary Ideology as their State Religion, the HRE is permanently dissolved, and ceases to exist.

## 18.8 NPR Emperor

If the HRE region is in play but the Emperor is controlled by an NPR, the Emperor starts with +3 `E` as usual, and `E` is adjusted as normal when Areas leave or rejoin the HRE.

Roll a 6-sided die at the end of the Round to see if `E` increases or decreases:

| Roll | Effect on `E` |
|------|---------------|
| 1 | Decrease `E` by 1 |
| 2–5 | Decrease `E` by 1 if roll is 2+ lower than current `E`. |
| 2-5 | Increase `E` by 1 if roll is 2+ higher than current `E`. |
| 6 | Increase `E` by 1 |

The number of Units that defend an HRE Area under attack is always as follows:

| Units defending Areas in NPR HRE |
|----------------------------------|
| Military Capacity of any defending NPR(s) |
| + 3 x `E` |
| – 2 x the number of HRE Areas containing non-HRE Units prior to this Turn |

### Vassalization and Annexation

An NPR Emperor cannot be Vassalized either by force or diplomatically.

If an NPR Emperor is Fully Annexed during Peace Resolution, the HRE dissolves and ceases to exist for the rest of the game.

## 18.9 Imperial Elections

**Advanced Rules**

If the Emperor has +4`E` or less when their current Ruler is replaced or discarded, an Imperial Election must be held.

The PR that receives votes from the most Elector Areas becomes the new Emperor. The PR that has the most `I` (including Imperial `I`) in an Elector Area receives the vote from that Area. Ties for most `I` in an Area, or for highest number of Elector votes, are decided by the current Emperor. An Elector Area with no NPR Provinces where all `v` belong to a single PR will automatically vote for that PR, if eligible.

A PR that has its Capital in an Elector Area gets the vote from that Area if eligible. Otherwise, that Elector Area does not vote.

To be eligible for (re)election as Emperor, a Realm must follow the official Religion of the HRE (if there is one). PRs that are not HRE Members, or those with Interregnums, can still be eligible. If no PR is eligible to become Emperor, the Emperor title remains with the current Emperor, but `E` drops by 2.

If `E` is below +3 following the election of a new Emperor, `E` increases by 1.

If a new PR is elected Emperor while the departed Emperor was *Defending the HRE*, the new Emperor may place a CB token on any non-HRE Realm at War with NPR HRE Members. The Imperial `m` stays at its current level, and will be available to the new Emperor under the normal conditions.

No election is held if the Emperor is controlled by an NPR.