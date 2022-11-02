fuel-usage
==========

Calculate totals with "tax on the tax" added on::

    # General formula
    total = ((litres * fuel_rate) + (litres * carbon_tax_rate)) * HST_tax_rate

    # Example calculation (the checksum for each entry)
    total = ((240.8 * 0.889) + (240.8 * 0.07741) * 1.13
          = 262.96402664
