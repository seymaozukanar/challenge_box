## HOW TO CREATE A CHALLENGE BOX 
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
- 
