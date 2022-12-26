# country-flags-py
A python async wrapper for countryflagsapi.com

# Example
```py
from countryflags import CountryFlags


async def main() -> None:
  async with CountryFlags() as session:
    status: int = await session.get("usa")
    
    print(status)


import asyncio


if __name__ == '__main__':
  asyncio.run(main())
```
![example_output](https://github.com/Marseel-E/country-flags-py/blob/main/countryflags/usa.png)
