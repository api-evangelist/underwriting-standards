# Underwriting Standards

A curated collection of data standards, APIs, and specifications used in insurance underwriting. This covers the landscape of industry-wide data interchange formats, protocol standards, and API ecosystems that enable carriers, MGAs, brokers, and InsurTech platforms to exchange underwriting data programmatically.

Key standards include ACORD (Property & Casualty, Life, Reinsurance), LIMRA LDEx (employee benefits), and emerging OpenInsurance initiatives.

## Standards

### ACORD Next-Generation Digital Standards (NGDS)

ACORD provides the insurance industry's primary data standards. The NGDS are JSON/YAML-based transaction-centric standards for RESTful APIs and microservices, covering Policy, Claims, Party, Product, and Reinsurance entities.

- **Website:** https://www.acord.org/
- **NGDS Documentation:** https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards

### LIMRA LDEx Data Exchange Standards

Free, collaboratively developed standards for exchanging employee workplace benefits data between carriers and benefits administration platforms. LDEx provides REST API endpoints compliant with OpenAPI 3.1.

- **Website:** https://www.limra.com/
- **Documentation:** https://www.limra.com/en/solutions-and-services/data-exchange-standards/ldex-overview/

## Artifacts

### JSON Schema

| File | Description |
|------|-------------|
| [json-schema/underwriting-standards-submission-schema.json](json-schema/underwriting-standards-submission-schema.json) | Schema for an insurance underwriting submission including risk, coverages, quotes, and documents |

### JSON Structure

| File | Description |
|------|-------------|
| [json-structure/underwriting-standards-submission-structure.json](json-structure/underwriting-standards-submission-structure.json) | Field-level documentation for the Underwriting Submission entity |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/underwriting-standards-context.jsonld](json-ld/underwriting-standards-context.jsonld) | JSON-LD context mapping underwriting terms to schema.org and FIBO ontology vocabulary |

### Examples

| File | Description |
|------|-------------|
| [examples/underwriting-standards-submission-example.json](examples/underwriting-standards-submission-example.json) | Example cyber liability underwriting submission following ACORD data standards |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/underwriting-standards-vocabulary.yml](vocabulary/underwriting-standards-vocabulary.yml) | Domain vocabulary covering underwriting process, risk assessment, coverage concepts, data standards, and InsurTech |

## Related Resources

- [ACORD Data Standards](https://www.acord.org/standards-architecture/acord-data-standards)
- [LIMRA LDEx Standards](https://www.limra.com/en/solutions-and-services/data-exchange-standards/)
- [ACORD Reference Architecture](https://www.acord.org/standards-architecture/reference-architecture)
- [Open Insurance Initiative](https://openinsurance.io/)
