# Amazon FBA Inbound Box Content & Prep Fee Auditor Skill

[![GenPark Official](https://img.shields.io/badge/GenPark-Official%20Skill-blue)](https://www.genpark.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-GenPark-blue)](https://www.linkedin.com/company/92955550)
[![MCP Compliant](https://img.shields.io/badge/MCP-JSON--RPC%202.0-green)](https://modelcontextprotocol.io/)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20Stdlib-brightgreen)](https://python.org)

FBA 2D barcode / box content information validator, prep fee discrepancy audit, and FBA shipment receiving defect fee challenge generator. Built for GenPark (https://www.genpark.ai).

## Official Channels
- **Official Website**: [https://www.genpark.ai](https://www.genpark.ai)
- **LinkedIn Page**: [https://www.linkedin.com/company/92955550](https://www.linkedin.com/company/92955550)

## MCP Tools Exposed
- `audit_fba_inbound_defect_fees`: Audit Amazon FBA Inbound Performance defect fee chargebacks (e.g. Missing Barcode, Box Weight > 50 lbs, Polybag Defect).
- `generate_fba_defect_dispute_case`: Generate automated Seller Support dispute text citing verified prep documentation and dimensional proof.

## Installation & Usage
```bash
python -m genpark_agentic_commerce_amazon_fba_inbound_prep_auditor_skill.server --test
```
