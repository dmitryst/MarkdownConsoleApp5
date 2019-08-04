# MarkdownConsoleApp5

| Объект в модели          | RETAIL                                                                | EVRAZ                                                       |
|--------------------------|-----------------------------------------------------------------------|-------------------------------------------------------------|
| тип сделки РД            | DealType_ Factoring                                                   | DealType_FactoringNoRegress                                 |
| LmFrameDealTypeCode      | "Факторинг c регрессом"                                               | "Факторинг без регресса"                                    |
|                          |                                                                       |                                                             |
| разновидность сделки РД  | DealKind_R_Standart_Retail                                            | DealKind_BR_ComBank_Retail                                  |
| LmFrameDealKindCode      | Регресс стандартный - Retail                                          | "Безрегресс (ком. банком) - Retail"                         |
|                          |                                                                       |                                                             |
| тип ГПФ                  | DealType_Factoring_GroupTransh                                        | DealType_ FactoringNoRegress_GroupTransh                    |
| LmGpfDealTypeCode        | "Факторинг с регрессом (групповая позиция финансирования)"            | "Факторинг без регресса (групповая позиция финансирования)" |
|                          |                                                                       |                                                             |
| разновидность ГПФ        | DealKind_R_Standart_Retail                                            | DealKind_BR_ComBank_Retail                                  |
| LmGpfDealKindCode        | "Регресс стандартный - Retail"                                        | "Безрегресс (ком. банком) - Retail"                         |
|                          |                                                                       |                                                             |
| код разновидности лимита | LimitKind_FactoringDebitor                                            | LimitKind_FactoringClient                                   |
| LmLimitKindCode          | "Факторинг с регрессом (финансирование поставщиков клиента-дебитора)" | "Факторинг без регресса"                                    |
