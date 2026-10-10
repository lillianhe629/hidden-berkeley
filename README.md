# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## Python environment

From this repository's folder, create and install the project environment:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

In VS Code, open `hw2_hidden_berkeley.ipynb`, choose **Select Kernel**, and select the Python interpreter in this repository's `.venv` folder. On macOS/Linux, it is `.venv/bin/python`. If you use a different machine later, repeat the setup commands there.

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources
Beyond the Bear is a guide designed for UC Berkeley students, especially those who are new to campus or want to discover useful resources beyond the classroom.

The guide introduces study spaces, research facilities, creative spaces, and student support services across Berkeley.

The original dataset contains eight campus resources. We added a ninth resource, the Student Learning Center (HB09), which provides academic support and tutoring services.


## Website checks

I reviewed official UC Berkeley webpages to verify resource information and improve access notes.

For the Jacobs Institute Makerspace (HB04), I reviewed the official website to  identify makerspace access requirements, including the Maker Pass and safety training.

For the Student Learning Center (HB09), I checked the official Economics Drop-in Tutoring webpage and confirmed:

- Drop-in tutoring does not require advance registration.
- Sessions take place on the first floor of the Student Center.
- Students should check the weekly schedule before visiting.
- Visitors must complete a sign-in form upon arrival.

I also confirmed that the Student Learning Center was not included in the original eight resources.

The guide retains all eight original resources and adds the Student Learning Center as the ninth entry.

Access information may change, so users should refer to the official websites before visiting.
