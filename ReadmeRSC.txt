11/19/2019
This is an end-to-end working example from djangogirls tutorial.
I am now going to extend this example to include the ability to upload and display 
images. The original working example is backed up as djangogirls_gf.

Main changes I am making:
pip install pillow (from myvenv). Pillow required for ImageField()
=> Successfully installed pillow-6.2.1

Update blog/models.py to include imagefield.

activate mvenv:
source myvenv/bin/activate

If I lose django admin password, can always generate a new one
(myvenv) python manage.py createsuperuser

