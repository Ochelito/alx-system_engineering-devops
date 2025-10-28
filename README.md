# alx-system_engineering-devops

## Task 0: Alias

**Objective:**  
Create a script that creates an alias.

- **Name:** `ls`  
- **Value:** `rm *`

**Example:**
```bash
julien@ubuntu:/tmp/0x03$ ls
0-alias  file1  file2
julien@ubuntu:/tmp/0x03$ source ./0-alias
julien@ubuntu:/tmp/0x03$ ls
julien@ubuntu:/tmp/0x03$
julien@ubuntu:/tmp/0x03$ \ls
julien@ubuntu:/tmp/0x03$


yaml
Copy code

---

✅ **Summary**
- `0-alias` → only this line:
  ```bash
  alias ls='rm *'