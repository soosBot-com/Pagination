# discord.py Paginator
#### This is a collection of paginators created for discord.py 2.0 views. Python 3.9+ & discord.ui required.
#

# How to use
1) Create a file called Pagination.py in your code. [It would be better if you made a .utils folder in your cogs, and created it in there.]

2) Import it into your code
    ```py
    import Pagination
    ```
    If you are using this as a utils file, import it like this
    ```py
    from .utils import Pagination
    ```
3) Create a list of embeds to paginate
    ```py
    embeds = [discord.Embed(title="First embed"), discord.Embed(title="Second embed")]
    ````
4) Start the pagenation
    ```py
    await Pagination.ButtonPagination().start(ctx, pages=embeds)
    ```
