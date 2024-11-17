# Boolean Difference Plus for Blender

**Boolean Difference Plus** is a Blender addon that extends the standard boolean difference operation, designed specifically with 3D printing in mind. Instead of removing the subtracted object, this addon preserves it, allowing you to fine-tune the design while maintaining the original piece.

## ✨ Key Features

- **Enhanced Boolean Difference:** Perform boolean difference operations without deleting the subtracted object, making iterative adjustments easier.
- **Tolerance Setting for 3D Printing:** Includes a customizable tolerance parameter (in millimeters) to compensate for common issues in 3D printing. This helps ensure a perfect fit for parts that need to snap together or fit into holes, which can often be slightly smaller after printing.
- **User-Friendly Interface:** Simple and intuitive UI within Blender for quick and efficient workflow integration.
- **Non-Destructive Workflow:** Maintain full control over both objects involved in the boolean operation, allowing for non-destructive editing.

## 🛠️ Use Cases

- Creating interlocking parts for 3D prints.
- Designing assemblies that require precise fitment.
- Rapid prototyping where iterative design changes are common.

## 📝 Requirements

- Blender **3.0** or later
- Compatible with both **mesh** and **curve** objects

## 🚀 Installation

1. Download the addon from the [GitHub releases](https://github.com/anfeo/insert_cut).
2. In Blender, go to **Edit > Preferences > Add-ons > Install** and select the downloaded file.
3. Enable the addon from the preferences panel.

## 📚 How to Use

1. Select the object you want to subtract **from**.
2. Select the object you want to use as the **cutter**.
3. In the addon panel, set the desired **tolerance** (in millimeters) if needed.
4. Click **Boolean Difference Plus** to apply the operation.

## 🐛 Issues and Feedback

If you encounter any issues or have suggestions for improvements, please open an [issue](https://github.com/anfeo/insert_cut/issues) on GitHub.

## 📝 License

This addon is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

Enjoy designing and happy 3D printing! 🎨🖨️
