# Miami GP + Everglades Trip Plan (May 2027)

**Trip context:** Miami Grand Prix weekend, early May 2027 (3 of us, tickets in hand). Staying on in South Florida for parks May 11-18, 2027: **Everglades National Park (main event)** and **Biscayne National Park (maybe)**. All park facts pulled live from the National Park Service data API at draft time; F1 facts from the official driver record.

---

## 1. Official park names and codes (as returned by NPS data)

| Park (official name, exactly as returned) | Park code | Designation |
|---|---|---|
| Everglades National Park | `ever` | National Park |
| Biscayne National Park | `bisc` | National Park |

- **Everglades National Park** — https://www.nps.gov/ever/index.htm — (25.37294225, -80.88200301) — Voice: 239-695-2000
- **Biscayne National Park** — https://www.nps.gov/bisc/index.htm — (25.490587, -80.21023851) — Voice: 786-335-3620 — email: bisc_information@nps.gov

Use these exact codes (`ever`, `bisc`) when booking tours or referencing park records.

---

## 2. Alerts currently in effect

### Everglades National Park (`ever`) — 3 alerts in effect

1. **"Current Alerts and Conditions"**
   - Type: **Park Closure (area inaccessible)**
   - Last updated: 6/27/2026
   - Description: "Be sure to review the Alerts and Conditions below before and during your visit for additional, up-to-date information on closures, cautions, and other current park conditions."
2. **"For entrance fees, we accept digital passes and credit/debit cards"**
   - Type: Information (non-emergency)
   - Last updated: 5/28/2026
   - Description: "Digital passes or credit/debit cards are the ONLY method of payment at all fee collection areas. Pre-paid digital passes are available online and may be purchased in advance."
3. **"Roadwork may cause delays on US 41/Tamiami Trail"**
   - Type: Caution (potential hazard)
   - Last updated: 5/28/2026
   - Description: "Current roadwork is ongoing along the park's northern boundary on US Highway 41/Tamiami Trail to raise the road for Everglades Restoration benefits. Drivers may experience up to 15-minute delays and should watch for personnel, equipment and slow downs."

### Biscayne National Park (`bisc`) — 3 alerts in effect

1. **"Camping and Docking at Boca Chita and Elliott Keys"**
   - Type: Information (non-emergency)
   - Last updated: 9/18/2026
   - Description: "Day Use Docking at Boca Chita and Elliott Keys: $25.00 Friday - Monday and Federal Holidays. Overnight Camping and Docking at Boca Chita and Elliott Keys: $60.00 per night. Payments must be made on site using the recreation.gov phone app."
2. **"Ride Share Services"**
   - Type: Information (non-emergency)
   - Last updated: 10/31/2023
   - Description: "Convoy Point grounds, Jetty Trail, kayak launch, and picnic area open at 7 a.m. and close at 5:30 p.m. If you are using a ride share service for transportation to and from the park, ensure ride share services can be onsite before closing time."
3. **"Boater Awareness"**
   - Type: Caution (potential hazard)
   - Last updated: 9/7/2022
   - Description: "Please use caution in park waters due to navigational markers that may be missing or moved due to unforeseen circumstances."

**Neither park has a blank alerts board** — both currently have 3 alerts in effect. The Everglades closure-typed alert ("Current Alerts and Conditions") is the park's rolling closure/conditions notice; re-check it close to travel since closures listed under it change.

### Closure count and share (calculator-verified)

- Combined alerts across both parks: 3 (Everglades) + 3 (Biscayne) = **6**
- Outright closures (type "Park Closure"): **1** (the Everglades "Current Alerts and Conditions" alert; Biscayne has none)
- Closure share: (1 / 6) × 100 = **16.666666666666664 % ≈ 16.67%**

---

## 3. Everglades events, May 11-18, 2027 (from NPS events calendar)

The park-service calendar **does** list event coverage for our window — one recurring event series, running daily including every day of May 11-18, 2027:

- **"Backcountry Boat Tour (Whitewater Bay)"** — Category: Regular Event — Location: Flamingo Marina — Times: All day, every day (our window included)
  - "Join a naturalist as you explore the Marjory Stoneman Douglas Wilderness. Trips depart hourly and visit either Whitewater Bay via Buttonwood Canal or Florida Bay."
  - Booking: Marina Activities Booth, reserve online at flamingoeverglades.com/boat-tours/, or call 855-708-2207.
  - Scheduling notes from the listing: Backcountry tours depart on odd hours (9, 11, 1, 3); Bay tours depart on even hours (10, 12, 2, 4). Backcountry tours are available year-round; Florida Bay tours are available November to April — our mid-May dates fall **outside** the Florida Bay tour window, so the bookable option in our window is the Backcountry (Whitewater Bay) tour.

That is the only listing on the Everglades calendar for May 11-18, 2027 — no ranger programs, festivals, or special events are on the calendar that far ahead.

---

## 4. Lewis Hamilton fact box (from official driver record)

| Fact | Value |
|---|---|
| Permanent car number | **44** |
| Three-letter driver code | **HAM** |
| Nationality | **British** |
| Date of birth (as returned by data) | **1985-01-07** |
| Age on our first park day, May 11, 2027 | **42** |

Age math (calculator-verified): born 1985-01-07, so his Jan 7 birthday falls before May 11, 2027 → 2027 − 1985 = **42**. He turns 43 on January 7, 2028.

---

## Data provenance

- Park names, codes, alerts, events: live NPS park-service data API (findParks, getAlerts, getEvents), queried at draft time.
- Hamilton facts: official driver record (driverId: hamilton), returned fields used verbatim.
- Arithmetic (closure share and age) run through a calculator, not mental math.
