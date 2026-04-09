# 🏛️ Banking

## 🧭 Why This Subdomain Matters

Banking workflows require controlled investigation, identity verification, fraud monitoring, and strict escalation paths across customer, transaction, and compliance systems.

## 💡 High-Value Use Cases

- 🕵️ suspicious transaction investigation
- 🪪 KYC and AML workflow orchestration
- 🏦 loan review support and document validation
- 📣 exception routing to specialists

## 🔄 Example Data Flow

```mermaid
flowchart TD
    A[Loan or Transaction Event] --> B[Credit and Fraud Agent]
    B --> C[Risk Assessment Agent]
    C --> D[KYC Verification Agent]
    D --> E{Manual Review Needed}
    E -->|Yes| F[Human Specialist]
    E -->|No| G[Controlled Approval or Rejection]
```

## 🧠 Capability Map

```mermaid
mindmap
  root((Banking Agents))
    Fraud
      Transaction Review
      Behavioral Patterns
      Alert Prioritization
    Compliance
      KYC
      AML
      Case Files
    Lending
      Credit Inputs
      Document Checks
      Decision Support
```

## 🧰 Workspace

- 🏛️ [Generators](generators/README.md)
- 💻 [Code](code/README.md)

