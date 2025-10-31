---

### 🧩 Code

```java
int[] nums = {4, 3, 2, 3, 1, 2};
```

---

### Step-by-step Dry Run

**Step 1:** `Arrays.sort(nums);`
After sorting →
`nums = [1, 2, 2, 3, 3, 4]`

---

**Step 2:** Create an empty list
`ans = []`

---

**Step 3:** Start the loop
`for (int i = 1; i < nums.length; i++)`

| i | nums[i-1] | nums[i] | Equal? | Action     | ans    |
| - | --------- | ------- | ------ | ---------- | ------ |
| 1 | 1         | 2       | No     | do nothing | []     |
| 2 | 2         | 2       | Yes    | add 2      | [2]    |
| 3 | 2         | 3       | No     | do nothing | [2]    |
| 4 | 3         | 3       | Yes    | add 3      | [2, 3] |
| 5 | 3         | 4       | No     | do nothing | [2, 3] |

Loop ends ✅

---

**Step 4:** Convert `ans` → array
`ans = [2, 3]`
So the final `result = [2, 3]`

---

✅ **Final Output:**

```
[2, 3]
```

---
