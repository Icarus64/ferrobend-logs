### Basic setup
- [x] New user in DB
	- [x] Local ([[2025-01-08]])
	- [x] Live ([[2025-01-08]])
- [x] Header adjust ([[2025-01-08]])
- [x] Login adjust ([[2025-01-08]])
- [x] Color code, task and dashboard adjust ([[2025-01-08]])
- [x] New table goods_receipt_note
	- [x] Local ([[2025-01-09]])
	- [x] Live ([[2025-01-08]])
- [x] New table goods_receipt_list
	- [x] Local ([[2025-01-09]])
	- [x] Live ([[2025-01-08]])
- [x] New GRN Modal prep
	- [x] Basic inputs ([[2025-01-09]])
	- [x] Change query to exclude empty POs for the modal dropdown ([[2025-01-09]])
	- [x] VPO Dependent product fetch ([[2025-01-09]])
		- [x] FG ([[2025-01-09]])
		- [x] SFG ([[2025-01-09]])
		- [x] RM ([[2025-01-09]])
	- [x] Product Dependent PO-Qty fetch ([[2025-01-09]])
	- [x] Row duplicate 
		- [x] div duplicate mechanism ([[2025-01-09]])
		- [x] Dropdown content duplicate ([[2025-01-09]])
		- [x] Prevent new row if VPO not selected condition ([[2025-01-09]])
	- [x] Remove duplicate row btn
		- [x] Removal mechanism ([[2025-01-10]])
		- [x] Styling ([[2025-01-10]])
	- [x] Change gr-qty to number input ([[2025-01-10]])
- [x] New GRN shortcut ([[2025-01-10]])
- [x] Auto focus for New GRN ([[2025-01-10]])
- [x] GRN Submission
	- [x] New db changes
		- [x] new table: goods_picture, goods_challan
			- [x] Local ([[2025-01-10]])
			- [x] Live ([[2025-01-10]])
		- [x] drop column (vgi) in grl and add to grn
			- [x] Local ([[2025-01-10]])
			- [x] Live ([[2025-01-10]])
		- [x] New column GRN no in GRN 
			- [x] Local ([[2025-01-10]])
			- [x] Live ([[2025-01-10]])
	- [x] Submission
	- [x] File upload ([[2025-01-10]])
	- [x] Num gen issue cause button and links to logout ([[2025-01-10]])
	- [x] Changing file input to add multiple images for challan ([[2025-01-13]])
	- [x] Picture file uploads ([[2025-01-13]])
- [x] GRN Delete ([[2025-01-13]])
	- [x] Adding picture in the chain of data to delete ([[2025-01-13]])
	- [x] Removing files from server during deletion ([[2025-01-13]])
- [x] Linking goods image to every product
	- [x] Change in DB 
		New Column grl_id in goods_picture
		- [x] Local ([[2025-01-15]])
		- [x] Live ([[2025-01-17]])
		- [x] Insert process changes ([[2025-01-15]])
- [x] GRN Update
	- [x] Data Fetch
		- [x] Normal DD data selection ([[2025-01-13]])
		- [x] VPO change handler for Update ([[2025-01-13]])
		- [x] Product change handler for Update ([[2025-01-13]])
		- [x] Product row cloner for Update ([[2025-01-13]])
		- [x] Duplicate row and its data fetch ([[2025-01-15]])
		- [x] Images for product fetch ([[2025-01-15]])
		- [x] Image btn and close btn alignment issue ([[2025-01-15]])
		- [x] Fetch Challans as btns ([[2025-01-15]])
		- [x] Image delete functionality ([[2025-01-16]])
		- [x] hidden grn value fetch ([[2025-01-16]])
		- [x] Update submission
			- [x] Delete rows that are removed ([[2025-01-17]])
			- [x] Insert new rows ([[2025-01-16]])
			- [x] Update old rows ([[2025-01-16]])
		- [x] Invoice file btn in GRN Update ([[2025-01-17]])
		- [x] Invoice file delete function refactoring for update ([[2025-01-17]])
		- [x] If an invoice already exists it should be deleted after the new one is added ([[2025-01-17]])
		- [x] Focus on next product for duplicate rows ([[2025-01-17]])
- [x] GR Qty max limiter ([[2025-01-17]])
- [x] No same product can be selected in the GRN ([[2025-01-17]])
### CRUD for Location & Crate
- [x] Crate CRUD
	- [x] Insert ([[2025-01-22]])
		- [x] Insertion ajax 
		- [x] Post submission process for single row
		- [x] Post submission process for clones
	- [x] Update ([[2025-01-22]])
	- [x] Delete ([[2025-01-22]])
- [x] Location CRUD
	- [x] Insertion AJAX ([[2025-01-22]])
- [x] View GRN modal ([[2025-02-07]])

### Fixes
- [x] Merging the pushed branch with conflicts ([[2025-01-16]])
- [x] Bug: nested prod rows in duplicate rows ([[2025-01-16]])
- [x] Bug: Duplicate row product DD is selected from the clone, make it null ([[2025-01-16]])
- [x] Bug: Uploading to second picture line sends it to first one ([[2025-01-16]])
		Fetch GRN php file was not incrementing the index for the loop for each GRL
- [x] Bug: Removing a prod row in GRN Update doesn't delete in submission ([[2025-01-17]])
		Goods Picture deleting was left out
- [x] Bug: New prod rows are not inserting in GRN Update submission ([[2025-01-17]])
- [x] Bug: Invoice submission doesn't stick to the DB ([[2025-01-17]])
		Error in the query
- [x] Bug: Block new product row gen limiter condition error 
- [x] Modify qty limiter to not reset but just give a warning and change color ([[2025-01-20]])
- [x] GRN used PO filter not working ([[2025-02-12]])
- [x] GRN new row product filter not working ([[2025-02-12]])

### Pagification of GRN 
- [x] GRN View ([[2025-05-06]])
- [x] GRN Add ([[2025-05-07]])
- [x] GRN Update ([[2025-05-07]])

### Fixes
- [x] Remaining line item VPOs now showing in GRN dropdown
- [x] Let invoice upload in GRN even after dependencies exist error handling check
