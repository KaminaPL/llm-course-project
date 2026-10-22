Aby odpowiednio odtworzyć środowisko na lokalnej maszynie z systemem Linux należy wywołać niniejsze komendy w katalogu projektu:


python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip


W celu zainstalowania pakietów potrzebnych do poprawnego działania projektu proszę wykonać niniejsze komendy w katalogu projektu:

python -m pip install -r requirements.txt
python -m pip freeze > requirements-lock.txt


Po wykonaniu powyższych czynności należy wykonać jeszcze komendę `python -m pip install -e`.


Projekt działa w dwóch trybach 'local' i 'api'. W jakim trybie projekt będzie działać ustala zmienna
środowiskowa LLM_MODE.
