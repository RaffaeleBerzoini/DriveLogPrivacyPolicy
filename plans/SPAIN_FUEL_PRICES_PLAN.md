# Spain Fuel Prices Implementation Plan

## Overview

Add support for Spain fuel prices in DriveLog by integrating the Spanish Ministry's public fuel price API.

## Data Source

- **Provider:** Spanish Ministry for Ecological Transition and the Demographic Challenge (MITECO / Ministerio para la Transición Ecológica y el Reto Demográfico)
- **Portal:** Geoportal Gasolineras — `https://geoportalgasolineras.es/`
- **API Endpoint:** `https://sedeaplicaciones.minetur.gob.es/ServiciosRESTCarburantes/PreciosCarburantes/`
- **License:** Reutilización de la información del sector público (Real Decreto 1495/2011)

## Phases

### Phase 1 — Update Privacy Policy ✅

Update the privacy policy (`README.md`) to include the Spanish fuel prices data source:

- [x] Add MITECO / Geoportal Gasolineras to the Third-Party Services section (English)
- [x] Update the Log Data section to reference the Spain API (English)
- [x] Update the Terms and Conditions — Third-Party Data section (English)
- [x] Add MITECO / Geoportal Gasolineras to the Servizi di Terze Parti section (Italian)
- [x] Update the Log Data section to reference the Spain API (Italian)
- [x] Update the Termini e Condizioni — Dati di Terze Parti section (Italian)

**Status:** ✅ Completed

### Phase 2 — App Integration 🔲

Integrate the Spanish fuel prices API into the DriveLog application source code.

**Status:** 🔲 Pending
