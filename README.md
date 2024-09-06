# AircraftMarket-
Aircraft Market - Module pour phpVMS / Aircraft Market - Module for phpVMS
Version Française
Description du module Aircraft Market
Aircraft Market est un module destiné aux compagnies aériennes virtuelles (VA) utilisant phpVMS. Ce module permet de gérer l'achat, la vente et la location d'avions, tout en simulant leur état et en intégrant des solutions de maintenance. Les VA peuvent également gérer des prêts financiers pour soutenir l'acquisition de nouveaux avions.
Fonctionnalités du module :
- Achat/Louer des avions : Les VA peuvent acheter des avions neufs ou d'occasion. Les avions d'occasion sont proposés à des prix réduits en fonction de leur état, qui se dégrade avec les heures de vol.
- Vente d'avions : Les VA peuvent mettre en vente leurs avions d'occasion. Ces ventes sont simulées et ne concernent pas d'autres VAs réelles. Le module génère automatiquement des offres virtuelles.
- Simulation de l'état des avions : L'état de chaque avion se dégrade progressivement en fonction des heures de vol et d'autres facteurs tels que la dureté des atterrissages.
- Maintenance des avions : Les VA peuvent choisir des entrepreneurs pour effectuer la maintenance des avions lorsque leur état se dégrade.
- Prêts financiers : Les VA peuvent prendre des prêts pour financer l'achat d'avions ou les réparations.
- Délais de production et de livraison : Lorsqu'une VA achète un avion neuf, un délai de production est simulé, après quoi l'avion est ajouté à la flotte.
Travail déjà effectué :
1. Création des tables et des migrations :
- aircraft_sales, maintenance_logs, maintenance_contractors, loans, aircraft_orders.
2. Contrôleurs : AdminController gérant les actions principales (vente, maintenance, prêts).
3. Routes : Définies dans admin.php (create-sale, log-maintenance, apply-loan, create-order).
4. Vues : Interfaces d'administration pour la gestion des avions.
Erreurs rencontrées :
1. Erreur de chemin pour les routes : 'Failed to open stream: No such file or directory'.
2. Problèmes potentiels de permissions.


English Version
Aircraft Market Module Description
Aircraft Market is a module for virtual airlines (VA) using phpVMS. This module allows for the management of aircraft purchases, sales, and leases while simulating their condition and integrating maintenance solutions. VAs can also manage financial loans to support the acquisition of new aircraft.
Module Features:
- Purchase/Lease Aircraft: VAs can buy new or used aircraft. Used aircraft are offered at reduced prices based on their condition, which degrades over time.
- Aircraft Sales: VAs can sell their used aircraft. These sales are simulated and do not involve real VAs. The module generates virtual offers automatically.
- Aircraft Condition Simulation: The condition of each aircraft degrades over time based on flight hours and other factors like landing quality.
- Aircraft Maintenance: VAs can choose contractors to perform aircraft maintenance when the aircraft condition deteriorates.
- Financial Loans: VAs can take loans to finance aircraft purchases or repairs.
- Production and Delivery Delays: When a VA buys a new aircraft, a simulated production delay occurs before the aircraft is added to the fleet.
Work Already Done:
1. Creation of tables and migrations:
- aircraft_sales, maintenance_logs, maintenance_contractors, loans, aircraft_orders.
2. Controllers: AdminController managing main actions (sales, maintenance, loans).
3. Routes: Defined in admin.php (create-sale, log-maintenance, apply-loan, create-order).
4. Views: Admin interfaces for aircraft management.
Errors Encountered:
1. Path error for routes: 'Failed to open stream: No such file or directory'.
2. Potential permission issues.



