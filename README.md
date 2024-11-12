!pip install pygit2==1.12.2
%cd / content
!git clone https://github.com/lllyasviel/Fooocus.git

%cd /content/Fooocus/models/upscale models/
!wget -0 fooocus_uspcaler_s409985e5.bin https://hugginface.co/lllyasviel/misc/resolve/main/fooocus_uspcaler_s409985e5.bin?download=true
%cd /content/Fooocus
!pyhton entry_with_update.py --share
