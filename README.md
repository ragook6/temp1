# temp1


echo "# temp" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ragook6/temp.git
git push -u origin main


cloudmap_service_module/
├── main.tf
├── variables.tf
├── outputs.tf
├── README.md
└── examples/
    └── basic_usage/
        ├── main.tf
        └── get-namespace-id.sh
