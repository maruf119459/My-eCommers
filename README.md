

## Get started
# Home Page View:<br>
<img src="Screenshot 2024-10-27 064443.jpg" width="800" hight="600">

1. Clone the repository:

```bash
git clone https://github.com/maruf119459/My-eCommers.git
```

2. Create virtual enviroment:

```bash
virtualenv env
source env/bin/activate # for Linux
.\env_name\Scripts\activate # for Windows
```

3. Install all the dependencies:

```bash
pip install -r requirements.txt
```

4. Change directory to `ecommerce`:

```bash
cd ecommerce
```

5. Run migrations:

```bash
py manage.py migrate
```

6. Run the server:

```bash
py manage.py runserver
```
