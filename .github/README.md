# 🧠 NextGenio – LLM-modell med Kritisk Tenkning (Fra Grunn)

**Versjon:** 0.1.0  
**Lisens:** MIT  
**Status:** Under utvikling  
**Kontakt:** Henrik Strand – steliaverditakst@gmail.com

---

## 📘 Om prosjektet

Dette prosjektet er en del av NextGenio-plattformen og bygger en liten, funksjonell LLM-modell fra bunnen av med fokus på kritisk tenkning, forklarbarhet og selvlæring. Koden og strukturen er inspirert av boken *Build a Large Language Model (From Scratch)* av Sebastian Raschka, men utviklet for nye forskningsformål innen AI og bevisst resonnering.

Prosjektet implementerer både modellarkitektur, treningsløp og validering – samtidig som det dokumenterer kravspesifikasjoner, use cases, og arkitekturvalg i tråd med ISO-standarder.

---

## 🧩 Hovedmål

- Skape en eksperimentell LLM med støtte for metakognitiv læring og kritisk evaluering av påstander  
- Utforske selvrefleksjon og forklarbarhet (XAI) i arkitektur og output  
- Dokumentere hele utviklingsprosessen fra idé til implementasjon  

---

## 🗂️ Mappestruktur

```bash
.
├── .github/                      # Issue templates og CI-workflows
├── appendix-A/                  # Introduksjon til PyTorch
├── appendix-D/                  # Ekstra funksjonalitet i treningsløkker
├── appendix-E/                  # Parameter-effektiv finetuning med LoRA
├── ch01/                        # Hva er LLM?
├── ch02/                        # Tekstdata og datalasting
├── ch03/                        # Oppmerksomhetsmekanismer
├── ch04/                        # GPT-modell fra bunnen
├── ch05/                        # Pretraining på umerkede data
├── ch06/                        # Finetuning for tekstklassifisering
├── ch07/                        # Finetuning for instruksjonsforståelse
├── pkg/llms_from_scratch/       # Python-pakken og underliggende moduler
├── setup/                       # Miljø- og installasjonsveiledning
├── docs/                        # Dokumentasjon, metoder og krav
├── admin/                       # Beslutninger (ADR), styring og eierskap
├── devcontainer/                # VS Code Dev Container konfigurasjon
├── pyproject.toml               # Python-bygge- og avhengighetsstyring
├── pixi.toml                    # Conda-bygget miljø for Pixi
├── requirements.txt             # Avhengigheter via pip
├── LICENSE.txt                  # MIT-lisens
└── README.md                    # Denne filen
