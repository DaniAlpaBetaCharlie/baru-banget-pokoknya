DateTimeSharePoint ge '@{formatDateTime(outputs('Convert_time_zone_1'),'yyyy-MM-ddTHH:mm:ssZ')}' and DateTimeSharePoint le '@{formatDateTime(outputs('Convert_time_zone'),'yyyy-MM-ddTHH:mm:ssZ')}'

length(body('Get_items')?['value'])
