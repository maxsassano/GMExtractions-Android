# Changelog

## [1.0.1] — 2026-09-26

### Fixed
- Crash con tabelle oltre 150 righe (rimosso limite, refactor a QTableView)
- Crash durante l'esecuzione della ricerca su Android 14+
- Reset incompleto dopo "Azzera" (ora svuota anche filtri e barra di stato)

### Added
- Dialog "Mostra dettagli" accessibile via long press
- Doppio tap su celle link (Sito, Email, Instagram, Facebook, Maps)
- Dialog di scelta arricchimento (Solo selezionate / Tutte con sito / Annulla)
- Contatore comuni e categorie nella finestra Info
- Scroll orizzontale fluido sulla tabella
- Guida aggiornata con le nuove gesture

### Changed
- Tabella rifatta con QTableView + QAbstractTableModel
- Colori di stato (giallo/verde/rosso) via Qt::BackgroundRole
- Selezione riga singola (era estesa)
- Rendering software raster (fix emulatore)

### Removed
- Limite di sicurezza 150 righe/tab
- Soglia automatica basata su numero tab × categorie

## [1.0.0-beta] — 2026-09-25

Prima versione Android.
