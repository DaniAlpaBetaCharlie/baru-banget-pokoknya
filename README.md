jam ge '@{formatDateTime(body('Convert_time_zone'),'yyyy-MM-ddTHH:mm:ssZ')}' and jam le '@{formatDateTime(body('Convert_time_zone'),'yyyy-MM-ddTHH:mm:ssZ')}'


length(body('Get_items')?['value'])
