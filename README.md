finanzas-app/
├── src/
│   ├── api/
│   │   ├── banks/
│   │   │   ├── ibercajaApi.js
│   │   │   ├── caixabankApi.js
│   │   │   ├── santanderApi.js      ← NUEVO
│   │   │   ├── bbvaApi.js           ← NUEVO
│   │   │   └── bankFactory.js       # (selector de banco)
│   │   ├── openbanking/
│   │   │   └── plaidService.js      # agregador Open Banking
│   │   └── authService.js
│   ├── components/
│   │   ├── TransactionItem.js
│   │   ├── BudgetCard.js
│   │   ├── AlertNotification.js
│   │   └── BankSelector.js          ← NUEVO
│   ├── context/
│   │   ├── TransactionContext.js
│   │   ├── BudgetContext.js
│   │   └── NotificationContext.js
│   ├── screens/
│   │   ├── HomeScreen.js
│   │   ├── TransactionsScreen.js
│   │   ├── BudgetScreen.js
│   │   ├── ReportsScreen.js
│   │   ├── BankConnectionScreen.js  ← NUEVO
│   │   └── SettingsScreen.js
│   ├── services/
│   │   ├── budgetService.js
│   │   ├── notificationService.js
│   │   ├── storageService.js
│   │   └── syncService.js
│   ├── utils/
│   │   ├── constants.js
│   │   └── formatters.js
│   └── App.js
├── __tests__/
├── .env.example
├── package.json
├── app.json
└── README.md
