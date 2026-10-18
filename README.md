# Educational software for long-term hydropower plant operation planning

A Python/PyQt5 desktop application for selecting the operating regime of the Votkinsk hydropower plant under water users' requirements. The regime is plotted on the dispatch chart, and the results can be exported to an MS Excel workbook.

Built in 2019 as the author's master's project at the Department of Hydropower and Renewable Energy, National Research University "MPEI" (Moscow, Russia).

Russian version: [educational_software_hpp_ru](https://github.com/alexshep-lab/educational_software_hpp_ru).

## Features

- choice of the input data variant and water users' constraints;
- long-term and medium-term regime calculation;
- plotting the regime on the dispatch chart;
- Excel report export (`xlsxwriter`).

## Screenshots

| Regime on the dispatch chart | Excel report |
|---|---|
| ![Regime](demonstration/Window%20appearance%20-%20longterm.JPG) | ![Excel](demonstration/Excel%20export.JPG) |

More screenshots and the project abstract are in [`demonstration`](demonstration).

## Running

```bash
pip install PyQt5 xlsxwriter
cd program
python EducationalSoftware_en.py
```

Run it from the `program` folder: the app keeps its state in `EducationalSoftware.tmp` in the current directory.

## Layout

- `program/EducationalSoftware_en.py` — main logic and application window;
- `program/window_bone.py` — UI layout;
- `program/initial_data.py` — input data;
- `demonstration/` — screenshots and abstract.

## Status

Archived student project from 2019 (v1.2). Developed with Python 3.5 and PyQt5 5.6; not tested on current versions. The code is published as is.

Author: Alexander Sysoev ([alexshep-lab](https://github.com/alexshep-lab)).
