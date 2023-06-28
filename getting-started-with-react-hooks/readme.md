# Udemy 課程

https://www.udemy.com/course/getting-started-with-react-hooks/

```xml
此課程會教導如何使用 react hook
分別以 class component 及 function component 兩種模式教學
```

## 課程說明

checkbox 為表示該課程是否必看

1. [ ] Welcome to React Hooks
2. [ ] Setup New create-react-app Project
       <br/>直接使用 https://github.com/HsunTsai/react-starter 依照 readme 將專案起起來
3. [x] OPTIONAL - REVIEW: Stateless Functional Components
       <br/> 簡介：說明目前有兩種型態 (1) class component (2) function component ， 並簡單介紹 function component
       <br/> 觀點：目前 function component 為主流，class component 已過時，但有很多舊程式仍使用 class component ，故還是要學一下
       <br/>但開發時請都使用 function component

4. [ ] OPTIONAL - REVIEW: Class-based React Components
       <br/>承上課程，講解 class component 的運作，因有蠻多 legacy code 還是會使用到，故還是需要了解一下

5. [ ] OPTIONAL - REVIEW: Array Destructuring
       <br/>陣列解構引導，可看可不看

6. [x] Invoking the useState Hook
       <br/>簡述 useState 的行為，可以不看直接看 7 先
7. [x] Destructuring and Using the useState Return Value
       <br/>useState 使用教學，必看
8. [x] Using the useState Hook to Build a Counter
       <br/>實作 counter 功能，透過 class component 及 function component 兩種寫法互相管換的較學(必看)
9. [x] CHALLENGE: Adding More Click Handlers
       <br/>透過 click handler 讓程式看起來更簡潔乾淨
10. [x] The useState Hook with an Object Argument
        <br/>把物件塞在 useState 中的教學，此撰寫風格非常不建議使用，撰寫習慣不好容易造成 crash
        <br/>雖然此方式不好，但是反向教材，文中還是有值得學習的地方
11. [x] Working with Multiple Pieces of State in a Hooks-Based Component
        <br/>承上課承，一樣不建議這樣寫，但可以學習操作 js

12. [x] OPTIONAL - REVIEW: Lifecycle Methods on Class-based Components
        <br/>class component 的生命週期講解
13. [x] Invoking the useEffect Hook
        <br/>useEffect 的簡易說明
14. [x] Cleaning Up by by Returning a Function from the Effect I
        <br/>承上課承
15. [x] Cleaning Up by by Returning a Function from the Effect II
        <br/>承上繼續介紹
16. [x] Limiting useEffect to Mounting and Unmounting
        <br/>useEffect ，當元件建立時，函式會被調用
        <br/>當元件被消滅時，return 的函示會被調用
        <br/>用於完善元件的生命週期

17. [x] The Second Argument to the useEffect Hook
        <br/>useEffect 用於監聽數值變化時，調用函示
18. [x] OPTIONAL - REVIEW: Event Listeners
        <br/>用純 js 註冊監聽教學
19. [x] Another useEffect Example: User Input
        <br/>用 useEffect 來註冊監聽，並於元件銷毀後 取消監聽

20. [x] OPTIONAL - REVIEW: React Context
        <br/>元件互相傳遞參數的方式，以古老的方法實現
21. [x] Invoking the useContext Hook
        <br/>元件互相傳遞參數的方式，以 useContext 的方法實現

```xml
22~24 課程必看，使用此方式撰寫程式碼
可有效減少耦合度，提高內聚
```

22. [x] Define a Custom Hook (User Keypresses)

23. [x] Another Custom Hook Example (Counter)

24. [x] CHALLENGE: Reusing Custom Hooks in Multiple Components

25. [ ] Conclusion
26. [ ] Bonus!
