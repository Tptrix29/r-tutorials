# Introduction to R for Data Science
[Website](https://tptrix29.github.io/r-tutorials/index.html) | [Email](mailto:pt2632@cumc.columbia.edu)

2024 BEST Program Course Documentation.

## Usage
1. Clone the repo: 
```bash
git clone https://github.com/Tptrix29/r-tutorials 
```

2. Open the project with **R Studio**.

## Update
1. Prepare your document:
- For lecture documents, please name your `Rmd` file in format `1-[index_number]-lec-[topic].Rmd` and update it to the root directory.
- For recitation documents, please name your `Rmd` file in format `2-[index_number]-rec-[topic].Rmd` and update it to the root directory.
- If you have any static resource to upload, please add it to `_main_files/` directory.

2. Update the contents in `index.Rmd` file. 

3. If you want to update documents, please refer to [Update](#update) part.

4. Run the following code in console of **R Studio**:
```r
bookdown::render_book()
```

5. Push the change to the GitHub repo:
You could use interface in **R Studio** or use the following command in your OS terminal:
```bash
cd path/of/project
git add .
git commit -m [commit-message]  # !!! Remeber to fill commit message !!!
git push
```
