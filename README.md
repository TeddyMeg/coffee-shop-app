# Coffee Shop App ☕️

Welcome to the Coffee Shop App! This is a simple coffee shop application built using React Native and Expo. The app allows users to browse and order coffee from a virtual coffee shop.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Screens](#screens)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with the Coffee Shop App, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/TeddyMeg/coffee-shop-app.git
   cd coffee-shop-app
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Start the app**:
   ```sh
   npx expo start
   ```

## Usage

After starting the app, you can open it in a development build, Android emulator, iOS simulator, or Expo Go. You can start developing by editing the files inside the `app` directory. This project uses file-based routing.

## Directory Structure

The directory structure of the Coffee Shop App is as follows:

```
coffee-shop-app/
├── app/
│  
│   ├── home.tsx
│   ├── menu.tsx
│   ├── contact.tsx
│   ├── components/
│   │   ├── CoffeeItem.tsx
│   │   ├── Header.tsx
│   ├── constants/
│   │   ├── Colors.ts
│   │   ├── Fonts.ts
│   ├── hooks/
│   │   ├── useAuth.ts
│   ├── navigation/
│   │   ├── AppNavigator.tsx
│   ├── assets/
│   │   ├── images/
│   │   │   ├── coffee.png
│   ├── app.json
│   ├── package.json
│   ├── tsconfig.json
│   ├── README.md
```

### Directory Details

- **app/screens/**: Contains the main screens of the app, such as HomeScreen, MenuScreen, OrderScreen, and ProfileScreen.
- **app/components/**: Contains reusable components like CoffeeItem and Header.
- **app/constants/**: Contains constant values like Colors and Fonts used throughout the app.
- **app/hooks/**: Contains custom hooks like useAuth for authentication.
- **app/navigation/**: Contains navigation-related files like AppNavigator.
- **app/assets/**: Contains static assets like images.

## Screens

### HomeScreen
The HomeScreen is the main screen of the app, displaying a welcome message and a list of featured coffee items.

### MenuScreen
The MenuScreen displays the full menu of available coffee items, allowing users to browse and select their favorite coffee.

### ContactScreen
The ContactScreen allows users to contact the Coffee Shop using either phone or sms.

## Contributing

Contributions are welcome! If you'd like to contribute to the Coffee Shop App, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to customize this README file to better suit your project's needs. If you have any questions or need further assistance, let me know!
