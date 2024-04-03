# Sales-Insights-
= Table.AddColumn(#"Filtered Rows1", "normalised_sum", each if [currency] = "USD" or [currency] = "USD#(cr)" then [sales_amount]*75 else [sales_amount])
