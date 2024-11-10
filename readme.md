
# Feature/API CONTACT PSIKIATER


### Configuration Steps
1. Clone the repository
```bash
git clone https://github.com/Mentalys-App/api-contact-psikiater.git
```
2. Go to the project directory
```bash
cd api-contact-psikiater
```
3. Install Dependency
- NPM
```bash
npm install
```
- Yarn
```bash
yarn install
```
- RUN
```bash
npm run dev
```

3. Need file .env and serviceAccount.json [contact me](c179b4ky4138@bangkit.academy) 

### Documentasi API
## 1. Get Data kontak psikologi
Mendapatkan seluruh data kontak.

```
GET http://localhost:3000/api/psychiatrists
```

#### Response Success

```json
[
  {
    "id": "5GvRbLGEeAsMNhLwOHv3",
    "name": "Dr. Tifa",
    "specialty": "Psychiatry",
    "location": "Magelang",
    "consultationFee": 300000,
    "contactNumber": "0802745035"
  },
  {
    "id": "9k2HFOIxxprqpnWwxaBB",
    "name": "Dr. Rikanesta",
    "specialty": "Psychiatry",
    "location": "Malang",
    "consultationFee": 500000,
    "contactNumber": "081234567890"
  },
  {
    "id": "A0709DXyUqgSmZR59ZL7",
    "name": "Dr. Arif",
    "specialty": "Psychiatry",
    "location": "Sleman",
    "consultationFee": 700000
  },
  {
    "id": "vhK5GHJV3Nszd7BF0Ulf",
    "name": "Dr. Tirta",
    "specialty": "Psychiatry",
    "location": "Jogja",
    "consultationFee": 200000,
    "contactNumber": "0802749506"
  }
]
```

## 2. Post Data baru kontak psikologi 
menambahkan data kontak psikologi.

```
POST http://localhost:3000/api/psychiatrists
```

#### Request

```json
{
  "name": "Dr. Rifda",
  "specialty": "Psychiatry",
  "location": "Sleman",
  "consultationFee": 700000,
  "contactNumber": "0802740026"
}

```
#### Response Success

```json
{
  "message": "Psychiatrist added successfully",
  "id": "FMoVFEG7GZGhYQetf65Q"
}
```

or access by link

```bash
  http://localhost:port/api-docs
```


## Screenshots
![Image](https://github.com/user-attachments/assets/39688334-161f-41ef-9b2b-7e7370d141a5)
![Image](https://github.com/user-attachments/assets/c509a660-44f4-492f-91e2-adad8be66c46)
![Image](https://github.com/user-attachments/assets/3c02c582-058e-452a-9d80-19c13073ae57)

