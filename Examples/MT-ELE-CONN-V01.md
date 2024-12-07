# MT-ELE-CONN-V01

**Domain:** ELE (Electrical)  
**Method ID:** CONN (Connector Inspection)  
**Version:** V01

---

## Purpose

Verify the integrity, cleanliness, and proper engagement of electrical connectors to ensure stable electrical pathways. Maintaining connectors in good condition prevents intermittent faults, voltage drops, and system failures.

## Applicability

- Aircraft Model: A360XWLRGA  
- Electrical connectors in wiring harnesses, junction boxes, and distribution panels.
- Prior use recommended after wiring checks or when intermittent electrical issues occur.

## Tools & Equipment

- **Visual Inspection Tools:** Flashlight, magnifying glass if necessary.  
- **Contact Cleaner (Approved):** For removing corrosion or dirt from connector surfaces.  
- **PPE:** Insulated gloves and safety glasses.

## Safety Notes

1. **Power Off Before Inspection:**  
   Disconnect aircraft electrical power before handling connectors.

2. **Avoid Contaminants:**  
   Ensure no foreign object debris (FOD) enters connectors during inspection or cleaning.

3. **Follow Approved Cleaners:**  
   Use only approved contact cleaners or solvents that meet regulatory and OEM specifications.

## Procedure Summary

1. **Pre-Inspection Setup:**
   - Confirm electrical power is fully disconnected.
   - Gather necessary tools and ensure contact cleaner is compatible with the connector materials.

2. **Visual Inspection:**
   - Examine connector housings for cracks, discoloration, or deformities.
   - Check pins and sockets for signs of bending, corrosion, or scoring.
   - Verify that the connector’s locking mechanism engages securely.

3. **Cleaning and Maintenance:**
   - If corrosion is present, apply a small amount of approved contact cleaner.
   - Gently remove debris with a soft, lint-free cloth or swab.
   - Avoid excessive force that could damage pins or coatings.

4. **Reassembly and Verification:**
   - Realign connectors and ensure they fit snugly.
   - Engage locking mechanisms and ensure they click or lock firmly.
   - If performing this check after a wiring inspection (`MT-ELE-WIRING-CHK-V02`), confirm continuity or voltage levels as needed.

5. **Record Findings:**
   - Document connector conditions, any replacements made, and results of functional checks.
   - Update maintenance logs and reference DMC modules for historical tracking.

## References

- **S1000D Data Module:** Refer to relevant electrical maintenance DMCs (e.g., `GAA-2400-MP-00-E-0003` for wiring maintenance procedures).
- **ATA Chapter:** 24 (Electrical Power)
- **Regulatory Compliance:** FAA AD 2024-05-12
- **Related Tokens:**
  - `MT-ELE-WIRING-CHK-V02` (Wiring Inspection)
  - `MT-CAL-MULTI-V01` (Multimeter Calibration), if continuity testing is needed post-connector reassembly.

## Integration with Digital Tools

- **AR/VR Guidance:**
  AR glasses can overlay connector identification and proper engagement instructions onto the technician’s field of view, highlighting connector locking points and providing quick reference videos.

- **IoT Sensor Data:**
  If IoT sensors detect voltage drops or intermittent faults, the CMS may recommend performing `MT-ELE-CONN-V01` to isolate connector issues early.

## Version History

- **V01:**
  - Initial method token created and integrated into MTL.
  - Provides a standardized approach to connector inspection, cleaning, and verification.

---

**End of Document**
