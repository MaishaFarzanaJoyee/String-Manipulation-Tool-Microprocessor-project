#  String Manipulation Tool — Microprocessor Project

**Course:** CSE341, BRAC University  

---

##  Project Overview

The **String Manipulation Tool** performs three different operations based on the user’s choice:

1. **Count the frequency of consonants** in a string  
2. **Check if a substring exists** within the main string  
3. **Remove vowels** from the given string  

This project demonstrates fundamental string processing logic in microprocessor programming.

---

## How It Works

1. The program asks the user **which operation** they want to perform.  
2. The user enters a string (input continues until the **Enter** key is pressed).  
3. Based on the selected operation:  
   - **Count Consonants:**  
     Displays the **number of consonants** (consider one-digit output).  
   - **Check Substring:**  
     Takes **two inputs** (main string and substring) and shows  
     **“Yes”** if the substring exists, otherwise **“No.”**  
   - **Remove Vowels:**  
     Displays the **string without vowels.**

---

## Example Outputs

| Operation | Input Example | Output Example |
|------------|----------------|----------------|
| Count consonants | `hello world` | `7` |
| Check substring | Main: `microprocessor`, Sub: `pro` | `Yes` |
| Remove vowels | `Education` | `dctn` |

---

## Implementation Notes
- Developed using **Assembly (EMU8086)**  
- Demonstrates **string handling, loops, and condition checks**  
- Focused on understanding **microprocessor-level operations**

---

📚 *A simple yet practical project to strengthen understanding of assembly-level string manipulation.*
