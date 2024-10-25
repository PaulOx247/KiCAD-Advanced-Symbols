# KiCAD-Advanced-Symbols

This project contains a comprehensive library of custom circuit symbols for use in KiCAD. The library includes various components like current and voltage arrows, AC and DC generators, resistors, capacitors, and measuring instruments. Each symbol follows standard conventions with additional customization for enhanced clarity and functionality in circuit design.

> **Note:** This library is compatible with KiCAD version **8.0.5** or higher. Make sure your KiCAD installation is up to date before using this library.

## Contents

The library includes the following categories of symbols:

### 1. Arrows (Current & Voltage)
- **Current and Voltage arrows** with various lengths, measured in Raster Units (RU), for indicating current flow and potential differences in circuits.

![image](https://github.com/user-attachments/assets/a629d48e-b4fb-4bc6-b0e7-4f7a162f6d39)

### 2. Generators (AC & DC)
- **AC and DC Generators** for providing alternating or direct current in different circuit designs.

![image](https://github.com/user-attachments/assets/22aa7aa6-e324-4932-b8ba-edb72365529b)

### 3. Passive Components (Resistors & Capacitors)
- **Resistors** (fixed and variable) and **Capacitors**, essential for controlling current, storing energy, and filtering signals.

### 4. Measuring Instruments (Voltmeters & Ammeters)
- **Measuring instruments** like voltmeters and ammeters for monitoring voltage and current.

![image](https://github.com/user-attachments/assets/76bbb5d0-30d4-4e99-acc5-098461ee6442)


## How to Add the Library to KiCAD

Follow these steps to import the custom library into KiCAD:

### Step 1: Download the Library
1. Clone or download the repository to your local machine:
   ```bash
   git clone https://github.com/PaulOx247/KiCAD-Advanced-Symbols.git
	```

### Step 2: Save the Library in the KiCAD Symbol Folder
1. Create a new folder inside the default KiCAD symbol folder to keep your custom symbols organized.
2. The standard path for KiCAD symbol libraries is:
- On Windows: `Documents\KiCad\8.0\symbols`
3. Create a new folder named `KiCAD-Advanced-Symbols` in this directory.
4. Unzip the downloaded GitHub file into this folder, or move the cloned repository files here.

### Step 3: Open KiCAD and Access Symbol Libraries
1. Open KiCAD and launch the **Symbol Library Editor**.
2. In the top menu, click on **Preferences** and then select **Manage Symbol Libraries**.

### Step 4: Add the Custom Library
1. In the **Global Libraries** tab, click on the **Add existing library to table** button (represented by a folder icon).
2. Navigate to the newly created `KiCAD-Advanced-Symbols` folder inside the KiCAD symbol directory.
3. Select the appropriate `.lib` file for the custom symbol library.
4. Once selected, confirm by clicking **Open**. The library will be added to your global symbol libraries list.

### Step 5: Save the Changes
1. After adding the library, click **OK** to save your changes in the Symbol Library Editor.

### Step 6: Using the Symbols
1. Open an existing or new schematic in KiCAD.
2. To place symbols, click on **Place Symbol** or press the **A** key.
3. In the symbol selection window, use the search bar to find your symbols by typing relevant keywords (e.g., "Arrow", "Generator", "Resistor").
4. Select the desired symbol and place it in your schematic.

---

### Recommendation: Pin the Library in the Schematic Editor
To easily access the custom symbols while working on your schematics, you can pin the library to the top of the symbol selection list in the Schematic Editor:

1. Open the **Symbol Library Editor**.
2. In the **Manage Symbol Libraries** window, find the custom library you just added in the list.
3. Right-click on the library name and select **Pin to Top**. This will pin the library to the top of the symbol selection window in the schematic editor.
4. Save the changes and close the **Symbol Library Editor**.
5. Now, whenever you open the **Place Symbol** window in the Schematic Editor, the pinned library will appear at the top of the list for quick and easy access.

---

## Screenshots

Here are some example images of the components in action:

![image](https://github.com/user-attachments/assets/9fabc51f-2764-412a-bf84-b49f3f733746)

---

### Black-and-White Color Scheme for Printing

If you're looking for a black-and-white color scheme for KiCAD schematics, you can use the custom scheme available [here](https://github.com/PaulOx247/KiCAD-BlackWhite-Schematic.git). This scheme ensures clarity and legibility when printing schematics in monochrome, while still allowing specific elements (like current flow arrows) to retain their assigned colors. Perfect for technical reports and documentation!

---

## License

This project is licensed under the [MIT License](LICENSE).
