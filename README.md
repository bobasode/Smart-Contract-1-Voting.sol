Kroki do uruchomienia kontraktu:
1. Zainstaluj Node.js i Hardhat.
2. Utwórz nowy projekt Hardhat: `npx hardhat`.
3. Skopiuj kod do pliku `contracts/Voting.sol`.
4. Skonfiguruj sieć testown (np. Sepolia) w hardhat.config.js.
5. Napisz skrypt deploy: `scripts/deploy.js`.
6. Uruchom deploy: `npx hardhat run scripts/deploy.js --network sepolia`.
7. Wejdz na Etherscan (testnet) i sprawdn swój kontrakt.
