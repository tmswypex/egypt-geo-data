# Egypt Governorates & Cities

JSON datasets of Egypt's governorates and cities/regions. Useful for address forms, database seeding, etc.

## Datasets

| File | Records | Contents |
| --- | ---: | --- |
| [governorates.json](governorates.json) | 27 | Governorates with Arabic and English names |
| [cities.json](cities.json) | 390 | Cities and regions linked to their governorates |


## Data examples

### Governorates

```json
{
  "id": 1,
  "name_ar": "القاهرة",
  "name_en": "Cairo"
}
```

### Cities and regions

```json
{
  "id": 133,
  "governorate_id": 1, // linked to the ID from the governorates dataset
  "name_ar": "مدينة نصر",
  "name_en": "Nasr City"
}
```

## Contributing

Everyone is welcome to contribute! You can propose changes, report missing or incorrect locations, improve Arabic or English names, or help with documentation. Contributions of all sizes are appreciated, including your first contribution.

Open an issue to share a suggestion or submit a pull request with your changes. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidance.

## License

This project is licensed under the [MIT License](LICENSE).
