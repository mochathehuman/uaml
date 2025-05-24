# §6. Command and Reporting

## Chain of Command
Issues must follow chain from lowest competent authority.

## Reporting Protocol
Incidents must be logged through proper channels.

```mermaid
graph TD
    A[Headquarters]
    A1[Judicial Review]
    B[Provost Corps]
    B1[Enforcement]
    G[JAGC]
    G1[Interpretation]
    G2[Appeals]
    G3[Investigations]

    A-->B
    A-.->A1
    B-->B1
    A-->G
    G-->G1
    G-->G2
    G-->G3
```