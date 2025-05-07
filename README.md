# Ball Sorting Mechanism — MEC322 Final Project

This repository contains the full engineering design, CAD files, and final documentation for our Ball Sorting Mechanism, developed as part of the **MEC322: Manufacturing Fundamentals** course at **Toronto Metropolitan University** (Winter 2025). The project was part of a semester-long team challenge that culminated in a real-world competition simulating industrial sorting under strict functional and material constraints.

## 📦 Project Summary

The objective was to **design and fabricate a physical mechanism** capable of picking up Ø 3/4" balls made of **metal, plastic, and Styrofoam** and sorting them into their corresponding colored boxes within a **1-minute limit**. Balls had to be sorted **without puncturing**, using only approved materials and fabrication techniques.

Points were awarded based on the material type:
- **Styrofoam** → 1 point
- **Plastic** → 3 points
- **Metal** → 5 points

### ✅ Our Competition Result:
- Successfully deposited **2 metal balls** (10 points total)
- Demonstrated a mechanically functional and optimized sorting mechanism
- Achieved maximum scoring efficiency by focusing on the **highest value target**

---

## 🛠️ Design Overview

Our final prototype was built with a **parallel four-bar linkage system** that allowed for precise control over both horizontal and vertical movement. Key components included:

- **Three-Fingered Claw**: Designed to cradle all ball types gently and effectively. An extended inner lever allowed ball ejection without excessive grip force.
- **Rotating Base**: Enabled radial access to each colored box from a central pickup position.
- **Rear Lever Extension**: Allowed for intuitive manual control without crossing the invisible “red line.”
- **Material-Actuated Arm**: Constructed with acrylic sheets and actuated via string tension to control movement—adhering to laser cut specifications.
- **Integrated Ball Pusher**: A simple yet effective innovation that ensured balls were *actively pushed* into box holes after scoop-up.
- **Elastic-Assisted Claw**: The claw used a **rubber band-based elastic mechanism** to generate **tension for grip and automatic closing**. This provided a spring-loaded hold to maximize retention of balls and allowed the claw to open when the string was pulled and close automatically upon release, ensuring a firm grip throughout the pickup and placement process.

These systems were iteratively refined through trial runs and simulation analysis to ensure compliance with spatial, material, and time constraints.

---

## 📐 CAD & Design Files

This repository includes:

- 🔩 `/solidworks/parts/`: All custom-designed SolidWorks part files (`.SLDPRT`)
- 🧩 `/solidworks/assemblies/`: Assembled mechanism files (`.SLDASM`)
- 📊 `/solidworks/drawings/`: DXF drawings used for laser cutting and dimensioning
- 📄 `/documents/final_report.docx`: Full engineering design report
- 📽 `/documents/arm_designs.pptx`: Concept evolution and design presentation

---

## 🎯 Competition Constraints

According to the project outline, all mechanisms were evaluated based on:
- **Functionality** under time pressure
- **Mechanical compliance** (no simple lever mechanisms; 4-bar linkage mandatory)
- **Manual operation limitations** (no hand can pass the invisible red line)
- **Material usage restrictions** (e.g., limited acrylic, screws, strings, bands)

Our design followed these requirements closely, leading to both a functional and robust solution.

---

## 🧠 Lessons Learned & Conclusion

Although our final design did not achieve full multi-ball sorting within the time frame, it demonstrated significant engineering merit in terms of:
- **Mechanical feasibility**
- **Innovative solutions** under material constraints
- **Design iteration based on testing**

The highlight was our ability to **successfully pick up and sort metal balls**, the most valuable in the scoring system. Future iterations could improve timing efficiency and automated ball-release control.

This project helped develop real-world engineering competencies such as:
- CAD modeling & simulation
- Iterative prototyping
- Linkage kinematics
- Manual actuation under real-time constraints
- Team collaboration and design reporting

---

## 🧩 SolidWorks File Descriptions

### 🔩 Parts (.SLDPRT)
- **1 of Arm.SLDPRT** – First segment of the arm linkage, typically anchored to the base or hinge point.
- **2 of Arm.SLDPRT** – Second segment in the four-bar linkage arm providing intermediate reach and articulation.
- **3 of Arm.SLDPRT** – Third segment extending the arm further for forward reach.
- **4 of Arm.SLDPRT** – Final or auxiliary link for full arm extension or connection to the claw.
- **Base.SLDPRT** – Main structural foundation that supports the entire mechanism.
- **Claw_Top.SLDPRT** – Top portion of the claw that helps in enclosing the ball when gripping.
- **Handle.SLDPRT** – Manually operated handle used to actuate the claw via attached string.
- **Holder.SLDPRT** – Supportive frame or bracket likely used to hold or align mechanical elements.
- **Lower_Claw1.SLDPRT** – Primary bottom claw component—paired with the secondary to scoop balls.
- **Lower_Claw2.SLDPRT** – Secondary bottom jaw of the claw providing support during pickup.
- **Mock Base.SLDPRT** – Prototype or test version of the base for alignment verification.
- **Mock Table.SLDPRT** – Prototype layout or jig simulating competition environment for testing.
- **Part1.SLDPRT** – Miscellaneous part; likely a placeholder or extra link/support in the mechanism.
- **Parts_Claw.SLDPRT** – Main claw component designed to grip and hold balls securely using a rubber band-tensioned mechanism.
- **RushGears__1187-8456.sldprt** – Standard gear part used for rotational control or torque transfer.
- **W25_SEC08_GR02_LAB2.SLDPRT** – Irrelevant lab part—can be excluded from GitHub repo.
- **basehinge.SLDPRT** – Hinge structure used to enable rotation of the base platform.

### 🧩 Assemblies (.SLDASM)
- **Arm Assembly (Not finished).SLDASM** – Partial assembly of the arm segments; used for alignment and linkage verification.
- **Assem1.SLDASM** – General mechanical assembly draft, possibly combining arm and base.
- **Assem2.SLDASM** – Likely an alternate or more refined version of the general assembly.
- **Claw_ASSEMBLY.SLDASM** – Complete assembly of the claw including top and bottom segments and elastic mechanism.
- **base assembly.SLDASM** – Full assembly of the base unit with hinge and support structures.

## 🏁 Reference Video

Watch the official project outline and explanation video (not a demo):  
📹 [YouTube Project Video](https://www.youtube.com/watch?v=mE8JKfSn5WI)
