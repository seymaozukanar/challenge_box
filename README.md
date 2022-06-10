# HOW TO CREATE A CHALLENGE BOX 

- Assume that I want to add a relevant challenge box to this page:

  ![2F3E613D-ECE8-4B0B-9D65-59CAC151573D](https://user-images.githubusercontent.com/44210825/173040949-6df7fe6f-fbbe-4e8f-aecc-3cb1615083ae.JPG)
  
- First, go to the corresponding file of this page from algorand/docs and find ‘index.md’

- Choose the part of the page where you want the box to reside

- * Copy-paste the following code snippet and enter the slug of the challenge that you want to insert:

    ```
      {% endverbatim%}
        {% generate_challenge_thumbnail challenge_slug=‘<your_challenge’s_slug>’ %}
      {% verbatim %}
    ```
  ![IMG_0567](https://user-images.githubusercontent.com/44210825/173041822-bc64e6a1-8258-4e35-9b96-073a66f15d57.jpg)

- Commit these changes to the staging/master branch

- After committing these changes, our servers will automatically load them in approximately 10 minutes

- That’s it! Now you have the box 🚀
