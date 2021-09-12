# discord.py Paginator
#### This is a collection of paginators created for discord.py 2.0 views. Python 3.9+ & discord.ui required.
#

# How to use
1) Install the library
    ```py
    pip install discord.py-pagination
    ```
2) Import it
    ```py
    import Paginator
    ```
3) Create a list of embeds to paginate
    ```py
    embeds = [discord.Embed(title="First embed"), discord.Embed(title="Second embed")]
    ````
4) Start the pagenation
    ```py
    await Paginator.Simple().start(ctx, pages=embeds)
    ```
