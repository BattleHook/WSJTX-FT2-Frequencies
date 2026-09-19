# WSJT-X FT2 Frequencies

Importable FT2 working frequencies for IARU Region 1.

## Region 1 frequencies

| Band | Frequency |
| 80 m | 3.578 MHz |
| 40 m | 7.052 MHz |
| 30 m | 10.144 MHz |
| 20 m | 14.084 MHz |
| 17 m | 18.108 MHz |
| 15 m | 21.144 MHz |
| 12 m | 24.923 MHz |
| 10 m | 28.184 MHz |

## How to import to WSJT-X

### 1. Download the file

Choose one file from this repository:

- `WSJTX FT2 Region 1.qrg.json` - recommended. All entries have `preferred: false`.
- `WSJTX FT2 Region 1 preferred.qrg.json` - optional. All entries have `preferred: true`.

Click the file name, click **Raw**, then use the browser download option. Save the file to a normal local folder such as `Downloads`. Do not copy the web page and do not change the `.qrg.json` extension.

### 2. Open WSJT-X settings

1. Start WSJT-X.
2. Open **File -> Settings**.
3. Open the **Frequencies** tab.

### 3. Merge the downloaded file

1. Right-click inside the Working Frequencies table.
2. Choose **Merge**. Do not choose **Load**: Load replaces the existing table.
3. Browse to the downloaded `.qrg.json` file in `Downloads` or the folder where you saved it.
4. Select it and confirm.
5. Click **OK** in Settings.

### 4. Check the result

The imported rows should show:

- IARU Region: `Region 1`
- Mode: `FT2`
- Frequencies: the eight values listed above

With the recommended file, choose your own preferred row in the Frequencies table. 
The preferred variant marks every row as preferred and is optional.

These are experimental/community operating frequencies. Check current band plans and local regulations before transmitting.
