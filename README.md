# unit-converter
prompt

make me a single file with html css js that converts units from metric to freedom units

changed background of selector

changed background of main box 

changed text color of formula

added new measurment unit

volume: {
                    fromLabel: 'From (liters):',
                    toLabel: 'To (gallons):',
                    convert: (l) => l * 0.264172,
                    reverse: (gal) => gal / 0.264172,
                    formula: '1 L = 0.264172 gal'
                },
