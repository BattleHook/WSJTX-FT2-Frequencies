# WSJT-X FT2 Frequencies

Importable FT2 working frequencies for IARU Region 1.

## Region 1 frequencies

| Band | Frequency | Description |
| --- | ---: | --- |
| 80 m | 3.578 MHz | FT2 Region 1 - 80 m |
| 40 m | 7.052 MHz | FT2 Region 1 - 40 m |
| 30 m | 10.144 MHz | FT2 Region 1 - 30 m |
| 20 m | 14.084 MHz | FT2 Region 1 - 20 m |
| 17 m | 18.108 MHz | FT2 Region 1 - 17 m |
| 15 m | 21.144 MHz | FT2 Region 1 - 15 m |
| 12 m | 24.923 MHz | FT2 Region 1 - 12 m |
| 10 m | 28.184 MHz | FT2 Region 1 - 10 m |

The descriptions above are also stored in the imported JSON and appear in the WSJT-X Working Frequencies table after merging.

## Windows import

### 1. Back up your current frequencies

Before importing anything, save a backup of the Working Frequencies table:

1. Start WSJT-X and open **File -> Settings -> Frequencies**.
2. Right-click inside the Working Frequencies table.
3. Choose **Save as**.
4. Save the file in a known folder, for example `Documents\\WSJT-X Backups`.
5. Keep this backup unchanged. It lets you restore your current table if needed.

### 2. Download an FT2 file

Choose one file from this repository:

- `WSJTX FT2 Region 1.qrg.json` - recommended. All entries have `preferred: false`.
- `WSJTX FT2 Region 1 preferred.qrg.json` - optional. All entries have `preferred: true`.

Click the file name, click **Raw**, then use the browser download option. Save the file to a known local folder such as `Downloads`. Do not copy the web page and do not change the `.qrg.json` extension.

### 3. Set the WSJT-X region (Optional)

1. In WSJT-X, open **File -> Settings -> General**.
2. Set **IARU Region** to **Region 1**.
3. Open the **Frequencies** tab.

### 4. Merge the downloaded file

1. In WSJT-X, open **File -> Settings -> Frequencies**.
2. Right-click inside the Working Frequencies table.
3. Choose **Merge**. Do not choose **Load**: Load replaces the existing table.
4. Browse to the downloaded `.qrg.json` file in `Downloads` or the folder where you saved it.
5. Select it and confirm.
6. Click **OK** in Settings.

### 5. Check the result

The imported rows should show:

- IARU Region: `Region 1`
- Mode: `FT2`
- Frequencies: the eight values listed above
- Description: the matching band description from the table above

With the recommended file, choose your own preferred row in the Frequencies table. The preferred variant marks every row as preferred and is optional.

These are experimental/community operating frequencies. Check current band plans and local regulations before transmitting.
