# Ashes of Creation Gathering Interactive Map

This project is an interactive map for the game Ashes of Creation, where you can add resource timers. The map allows users to mark locations, set timers for resource respawns, and manage various markers with additional functionalities like sound notifications and Discord links.

## Features

- **Interactive Map**: Click on the map to add markers for resources or bosses.
- **Timers**: Set timers for resource respawns and get notified when the time is up.
- **Marker Management**: Lock markers, toggle auto-delete, and set marker rarity.
- **Export/Import Markers**: Export your markers to a JSON file and import them back.
- **Sound Notifications**: Enable sound notifications for specific markers.
- **Discord Links**: Attach Discord links to markers for easy reference.
- **Local Storage**: Save markers to local storage and load them back.

## Getting Started

### Prerequisites

- A web browser with JavaScript enabled.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/ashes-gathering-map.git
    ```
2. Navigate to the project directory:
    ```sh
    cd ashes-gathering-map
    ```

### Usage

1. Open `ashesmap.html` in your web browser.
2. Use the map to add markers by clicking on the desired location.
3. Set timers, manage markers, and use the export/import functionalities as needed.

### Marker Management

- **Add Marker**: Click on the map and provide a name for the marker.
- **Set Timer**: Use the timer buttons in the marker popup to set a timer.
- **Lock Marker**: Prevent the marker from being dragged by toggling the lock button.
- **Auto-Delete**: Enable or disable auto-delete for markers when the timer reaches -24 hours.
- **Set Rarity**: Assign a rarity to the marker (Rare, Heroic, Epic, Legendary).
- **Sound Notifications**: Set a sound threshold to get notified when the timer is about to end.
- **Discord Link**: Attach a Discord link to the marker for easy reference.
- **Export/Import**: Export markers to a JSON file and import them back to the map.

### Export/Import Markers

- **Export Markers**: Click the "Marker exportieren" button to export markers to a JSON string.
- **Import Markers**: Click the "Marker importieren" button and paste the JSON string to import markers.

### Local Storage

Markers are automatically saved to local storage when you close the browser. You can load saved markers by clicking the "Gespeicherte Marker laden" button.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Leaflet](https://leafletjs.com/) - An open-source JavaScript library for mobile-friendly interactive maps.
- [Ashes of Creation](https://ashesofcreation.com/) - The game for which this map is created.
