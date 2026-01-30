# The Roman Microlensing Trifecta  
## Building Discovery Infrastructure for Invisible Objects  

**Bart Salazar & Brad Devowe**  
*Community contributors to Roman‑era science infrastructure*

---

## Executive Summary

The **Nancy Grace Roman Space Telescope** will transform time‑domain astronomy in the Galactic bulge, enabling the first large‑scale census of isolated stellar remnants—**black holes, neutron stars, and free‑floating planets**—through microlensing and astrometric measurements.

However, Roman cannot achieve this goal in isolation.

This white paper argues that **three small, carefully curated historical datasets**, ingested into the **Mikulski Archive for Space Telescopes (MAST)**, will unlock Roman’s full discovery potential. Together, these datasets form a **microlensing trifecta**—providing the **temporal**, **astrometric**, and **parallax** context Roman needs to convert detections into definitive physical measurements.

Rather than proposing a single massive archive ingestion, we demonstrate why **targeted, low‑cost, community‑curated datasets** outperform monolithic solutions in scientific return, accessibility, and mission readiness.

---

## Why Microlensing Needs History

Microlensing is fundamentally a **time‑integrated phenomenon**.

Key physical parameters—**lens mass, distance, and velocity**—are not fully constrained by any single observation. Long‑timescale events, especially those produced by massive dark lenses, unfold over years and often require **multi‑epoch, multi‑platform context** to resolve degeneracies.

- Ground‑based surveys such as **OGLE** and **KMTNet** provide long temporal baselines  
- Space‑based missions such as **Spitzer** provide parallax leverage  
- **Roman** will add precise **astrometric microlensing** measurements  

No one dataset is sufficient.  
**Together, they are transformative.**

---

## Why Roman Needs Context

Roman will measure the **angular Einstein radius (θE)** for thousands of microlensing events—an ability unmatched by any previous mission. Yet **θE alone does not yield lens mass**.

To determine mass definitively, Roman measurements must be paired with:

- Historical microlens parallax (**πE**) data  
- Long‑baseline light‑curve characterization  
- Pre‑identified high‑priority candidates for dark remnants  

Without these inputs, Roman risks rediscovering candidates **without the ability to immediately confirm their nature**.

**Archives are not passive repositories.  
They are active components of discovery.**

---

## The Trifecta: Three Complementary Datasets

### 1. OGLE–Gaia Long‑Timescale Microlensing Seed Catalog  
**Role:** Candidate identification and astrometric context  

**Contribution:**
- Identifies rare, long‑duration events (*tE ≳ 100–300 days*)  
- Incorporates **Gaia** proper motions and parallaxes  
- Flags high‑probability **black hole and neutron star** lenses  

This dataset narrows Roman’s search space to the most physically informative events.

---

### 2. Spitzer Microlens Parallax Catalog  
**Role:** Mass degeneracy breaking  

**Contribution:**
- Provides **πE** measurements from a ~1 AU space‑based baseline  
- Enables direct mass determination when combined with Roman **θE**  
- Preserves a **unique, no‑longer‑repeatable observing geometry**  

This dataset transforms Roman astrometry into **definitive mass measurements**.

---

### 3. OGLE–KMTNet Trifecta Light‑Curve Catalog  
**Role:** Temporal completeness and anomaly recovery  

**Contribution:**
- Combines long‑baseline **OGLE** monitoring with high‑cadence **KMTNet** coverage  
- Recovers short‑duration features missed by single surveys  
- Enables robust modeling of complex events  

This dataset ensures Roman inherits a **science‑ready temporal record**, not fragmented light curves.

---

## Why Three Small Datasets Beat One Massive One

| Approach | Massive Ingestion | Trifecta Approach |
|--------|------------------|------------------|
| Cost | High | **Very Low** |
| Review Complexity | Large | **Minimal** |
| Community Reuse | Limited | **Broad** |
| Scientific Focus | Diffuse | **Targeted** |
| Time to Impact | Long | **Immediate** |

Each dataset:
- Is **< 1 GB**  
- Is **public**  
- Serves a **distinct, non‑redundant role**  
- Aligns directly with Roman’s primary Galactic science goals  

Together, they form **discovery infrastructure**, not a single‑use product.

---

## Why Archives Matter as Much as Telescopes

Roman’s success will not be measured solely by photons collected, but by:

- How quickly discoveries can be validated  
- How broadly the community can participate  
- How effectively past and future missions are connected  

MAST’s role is not just to store Roman data—but to **activate it**.

By hosting these datasets as **High‑Level Science Products (HLSPs)**, MAST enables:

- Immediate co‑analysis  
- Reproducible workflows  
- Democratized access to high‑impact science  

---

## Community‑Driven Infrastructure Works

This trifecta proposal was assembled by **two members of the public**—not as outsiders, but as engaged participants in the Roman science ecosystem.

We believe that:
- **Space science belongs to everyone**  
- **Good data organization accelerates discovery**  
- **Flagship missions are strongest when communities are included early**  

These submissions are a small but concrete example of that philosophy in action.

---

## Final Thought

Some discoveries don’t happen because we look harder.

**They happen because we connect what we already have.**

This trifecta is about making those connections—so Roman can turn fleeting lensing events into a **lasting census of the invisible universe**.


## License

This project is released under the MIT License.  
See the `LICENSE` file for details.
