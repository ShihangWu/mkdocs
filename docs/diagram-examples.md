<!--
 * @Author: ShihangWu 2478677199@qq.com
 * @Date: 2025-10-24 23:16:37
 * @LastEditors: ShihangWu 2478677199@qq.com
 * @LastEditTime: 2025-10-24 23:26:47
 * @FilePath: \my-project\docs\diagram-examples.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# Diagram Examples

## Flowcharts

```mermaid
graph LR
  A[Start] --> B{Failure?};
  B --> |Yes| C[Investigate...];
  C --> D[Debug];
  D --> B;
  B --> |No| E[Success!];
```

## Sequence Diagrams

```mermaid
sequenceDiagram
    autonumber
    Server->>Terminal: Send request
    loop Health
        Terminal->>Terminal: Check for health
    end
    Note right of Terminal: System online
    Terminal-->>Server: Everything is OK
    Terminal->>DataBase: Request customer data
    Database-->>Terminal: Customer data
```