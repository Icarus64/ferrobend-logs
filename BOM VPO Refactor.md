1. [x] Fix SO-Goods-Map (Update & View) ([[2024-10-22]])
2. [x] Fix BOM
	1. [x] Alter so_goods_map to have FK of sq_line_items ([[2024-10-22]])
	2. [x] Fix so_goods_map submission ([[2024-10-22]])
	3. [x] Modify so_goods_map submission for qli column ([[2024-10-22]])
	4. [x] Fix Query & Table UI ([[2024-10-22]])
		1. [x] For RM
		2. [x] For SFG
		3. [x] For FG
	5. [x] Fix SFG Modal & DB ([[2024-10-22]])
		1. [x] DB Fixed
		2. [x] Modal Fixed
		3. [x] Submission and Update
	6. [ ] Fix  RM Modal & DB
		1. [x] Move RM-(Category, Schema & Products) outside to Master/
		2. [ ] RM Products in RM Modal
			1. [x] RM Product Modal (Add/Update/Delete) ([[2024-10-23]])
			2. [ ] RM Size Group Modal (Add/Update/Delete)
			3. [x] RM BOM (Add/Update/Delete) ([[2024-10-24]])
				1. [x] Submission
				2. [x] Page load query
				3. [x] Post Add & Update
				4. [x] Delete
			4. [x] Bring RM Cat, Form and Size group to RM Modal instead of RM Product ([[2024-10-24]])
				1. [x] Make the UI work
				2. [x] Unit weight formula
				3. [x] Submission
					1. [x] Modify the db
					2. [x] After submission
				4. [x] Update
				5. [x] Delete
			5. [ ] Final touches to the BOM page ([[2024-10-25]])
				1. [x] Fix post Add-Update process
				2. [x] Hide RM UOM
				3. [x] Fix update/submit button in modal
			6. [x] Fix so_goods_map, no size error ([[2024-10-25]])
			10. [x] MOC Lock in BOM RM ([[2024-10-25]])
			11. [x] Duplicate line item issue ([[2024-10-25]])
			12. [x] Fix tot_req ([[2024-10-25]])
			13. [x] Move density near category ([[2024-10-25]])
			14. [x] Search function in BOM ([[2024-10-28]])
			15. [x] Drawing in BOM Modal ([[2024-10-28]])
			16. [x] Defaults for SFG ([[2024-10-28]])
			17. [x] RM Schema update issue ([[2024-10-29]]) 
3. [x] Fix BOM-List in Purchase
	1. [x] FG ([[2024-10-29]])
	2. [x] SFG ([[2024-10-29]])
	3. [x] RM ([[2024-10-29]])
4. [x] Fix Purchase Order
	1. [x] New PO UI Rendering
		1. [x] FG ([[2024-10-29]])
		2. [x] SFG ([[2024-10-29]])
		3. [x] RM ([[2024-10-30]])
	2. [x] PO View
		1. [x] FG ([[2024-10-30]])
		2. [x] SFG ([[2024-10-30]])
		3. [x] RM ([[2024-10-30]])
	3. [x] Old PO insert
		1. [x] FG ([[2024-10-30]])
		2. [x] SFG ([[2024-10-30]])
		3. [x] RM ([[2024-10-31]])
	4. [x] Update
		1. [x] FG ([[2024-10-31]])
		2. [x] SFG ([[2024-11-06]])
		3. [x] RM ([[2024-11-06]])
5. [x] Create col (hsn_id in bom_rm) in live server ([[2024-10-31]])
6. [x] Phone no in PO/View ([[2024-11-06]])
7. [ ] Quantity in RM



NOTE: RM Data is deleted (believed to be used in BOM RM to store RM Sizes )